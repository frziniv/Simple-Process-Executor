# Simple-Process-Executor
A simple Python script to demonstrate a basic process execution and Git workflow.
# main.py
import time

def execute_process(process_name):
    """A function to simulate running a process."""
    print(f"Starting the '{process_name}' process...")
    time.sleep(2)  # Simulate a 2-second task
    print(f"Process '{process_name}' completed successfully.")

if __name__ == "__main__":
    task = input("Enter the name of the task to execute: ")
    if task:
        execute_process(task)
    else:
        print("No task entered. Exiting.")
