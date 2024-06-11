# tutorials


## Screen Processes
### Starting a process
- First install screen = **apt install screen**
- Create a screen instance - i believe a screen is like a small vm - by typing = **screen**
- Go to your service and run it, if it is a python with a venv first = **source venv/bin/activate** = **python -m app.serviceName**
- Press **ctrl a and ctrl d** at the same time -  it will detach from the current screen/session but the process will keep running
- To access a session write **screen -r pid.screenName** and you will see the process running inside it and you can edit it and detach again
- To rename a process type **screen -S pid.**oldName** -X sessionname **newName****
