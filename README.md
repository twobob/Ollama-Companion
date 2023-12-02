# Ollama Companion



* Made as much as possible modulair
* Added API endpoint configuration
* Combined openai and ollama endpoints
* Modelfile creator better overview
* Using shared dictionary 
* HF token encryption to be used with 
* HF repo creation and folder upload


# Modularity

All pages are rebuild into modules this makes it easir to maintain a good overview of the codebase and develop on smaller pieces.


# HF token encrypion

Add you tokken in the encrypter and save this somewhere you need this to create and push to huggingface repos.


# HF repo creater and uploader

Define a folder and upload this as a repo to HF



### TODOD MINDMAP

* add different dependency for aria2c









### Python schedular fo polling api

from apscheduler.schedulers.background import BackgroundScheduler




def my_task():
    print("Scheduled task executed!")

# Create a scheduler instance
scheduler = BackgroundScheduler()

# Schedule the task to run every 30 seconds
scheduler.add_job(my_task, 'interval', seconds=30)

# Start the scheduler
scheduler.start()

# Keep the script running to allow the scheduler to execute tasks
try:
    while True:
        pass
except (KeyboardInterrupt, SystemExit):
    # Shut down the scheduler gracefully on interruption
    scheduler.shutdown()
