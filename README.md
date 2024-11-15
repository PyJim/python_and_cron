# Lab: Setting Up a Python Cron Job

## Objectives
1. Create a Python script to restart a service.
2. Clear a specified temporary folder.
3. Set up a cron job to run the script at specified intervals.

## Prerequisites
- A Unix-based system (Linux/Mac)
- Python installed on the system
- Appropriate permissions to manage services and cron jobs

## Step 1: Create the Python Script
1. Create a new directory for your script: `mkdir ~/cron_jobs && cd ~/cron_jobs`
2. Create a new Python script: `nano manage_service.py`
3. Add the necessary code to restart a service and clear a temporary folder.
4. Save and exit the script.

## Step 2: Make the Script Executable
1. Run `chmod +x manage_service.py` to make the script executable.

## Step 3: Test the Script
1. Run the script manually to ensure it works.

## Step 4: Set Up the Cron Job
1. Open the crontab for editing: `crontab -e`
2. Add a new cron job to run the script at your desired schedule.
3. Save and exit the crontab editor.

## Step 5: Verify the Cron Job
1. List your cron jobs to verify the entry.
2. Check the log file after the scheduled time to see if the script ran successfully.
