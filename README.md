Tasks: task_one, task_two, and task_three are example functions that print a message.
Schedule: Each task is scheduled at different intervals. task_one runs every 10 seconds, task_two every 30 seconds, and task_three at the 15-second mark of every minute.
Multithreading: The scheduler runs in a separate thread so it doesn’t block other code. This is especially useful if you need to run other code alongside the scheduler.
Run: The run_scheduler() function keeps checking if any tasks are pending and runs them when scheduled.
