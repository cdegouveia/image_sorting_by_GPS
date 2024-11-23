Pyicloud might not immediately work for you. A few weeks ago Apple changed security features that only an updated module will be able to compensate for. 
In the meantime please donload base.txt. from this discussion https://github.com/picklepete/pyicloud/issues/456 . 
Rename the file to base.py and replace the version installed in your module's folder in your computer with this new file. Also minor script change to the authentication portion of the script. 
This should fix the issue. It did for me.
