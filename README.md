*****************
Sync Nexus
*****************

Version-1.0.2

Harjit @2025, mbmaster.pc@gmail.com

Sync Nexus is an open source tool for the folders synchronization task in the Windows-OS.  This software does not gives any gurantee or warranty for its operation. User must give it a try or hands on operation on test directories before putting Sync Nexus into the operation.

Sync Nexus allows to add multiple tasks for different directories to create backup. It provides only one way synchronization from Source --> Destination. It does not changes any folder/file in the source directory. 

It provides an exception rules list for the security of source directory to prevent any write operation. It provides a check function to ensure that user have not choosen a protected directory as a destination for the sync based on the defined rules.

Operation:

 - Start- Start the all tasks in the list.
 - Stop- Stop all the tasks in the list.
 - Add- Add new task.
 - Edit- Edit existing task based on the selected ID of task. 
 - Delete- Delete selected task based on the selected ID of task. 
 - Rules- Add exception rules directories in the rule list.
 - Auto Start- Add application to auto start while computer log on.
 - Run In Tray- If checked, the application will be run in the system tray.
 - Export Logs- Export logs available in the grid.
 - Clear Logs- Right click on the logs to clear.

Parameters:

- ID- Id is a uniqe number for the task identity.
- Enable- Enable or disable task for the operation on start action.
- Source- Add, Browse or Drag/Drop the source directory. (Source directory is which the backup needs to be created)
- Destination- Add, Browse or Drag/Drop the destination directory. (Destination directory where source files will be copied)
- Destination IP- Network drive IP address of destination to check the availability before operation.
- Sync On Midnight- Enable synch on midnight.
- Sync On Start- Enable synch once task is started.
- Delete Extra In Destination- Delete extra files from destination, which are no longer part of the source directory.
- Use Watcher- Watcher will monitor any change in the source directory.
- Watcher Delay- Any change captured in watcher will synch after defined delay.
- Error Delay- Retry delay incase of any error.
- Comment- User defined comment for the task.     
            
Screenshots:

![Screenshot-1](https://github.com/user-attachments/assets/8ed97b65-663e-4f28-9315-739a66d45138)

![Screenshot-2-2](https://github.com/user-attachments/assets/3ab767d8-636e-4516-bb49-97d976dafb82)

![Screenshot-3-2](https://github.com/user-attachments/assets/16c78285-7488-4cbf-9a4b-c88015886308)

Change Logs:
- 08-02-25: Version-1.0.2 (R1) - Added new functions.
- 14-02-25: Version-1.0.2 (R2) - UI enhancement.
