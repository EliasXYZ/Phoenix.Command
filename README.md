# Phoenix.Command
Open TextEdit and create a new file
Convert it to plain text by clicking Format > Make Plain Text
Add your commands, one per line. For example, you could do:
#! /bin/bash
cd ~/Desktop
mkdir myCoolFolder
cd myCoolFolder

Run chmod u+x ~/Desktop/myCommandScript.command in your terminal, where ~/Desktop/myCommandScript.command is the path to your script. This will give the terminal permission to run the file.

You're done! Double-click the file to run. Dragging over the terminal icon will also work.
Notes:
If you need to do something that requires root (admin) access, you can prefix your command with sudo. When the script runs, you'll have to enter your password (and be an administrator)
If the end user isn't an administrator, but you need to do something that required root access, you can use su someAdminName, which will perform the command as someAdminName (you'll need his password).
