# Lifecycle-of-components
* This program relate with a component lifecycle *

  
Activity Lifecycle:

onCreate(): Called when the activity is first created.
onStart(): Called when the activity becomes visible to the user.
onResume(): Called when the activity starts interacting with the user.
onPause(): Called when the system is about to start a background activity.
onStop(): Called when the activity is no longer visible to the user.
onDestroy(): Called before the activity is destroyed.
Service Lifecycle:

onCreate(): Called when the service is created.
onStartCommand(): Called when the service is started.
onBind(): Called when another component wants to bind with the service.
onUnbind(): Called when all clients have disconnected from a particular interface.
onRebind(): Called when new clients have connected to a previously unbound interface.
onDestroy(): Called when the service is no longer used and is being destroyed.
Broadcast Receiver Lifecycle:

No specific lifecycle methods for BroadcastReceiver, as they are typically short-lived. They receive broadcasts, process them in the onReceive() method, and then complete.
ContentProvider Lifecycle:

onCreate(): Called when the content provider is created.
query(): Called when a client requests data.
insert(): Called when a client wants to insert data.
update(): Called when a client wants to update data.
delete(): Called when a client wants to delete data.
getType(): Called to get the MIME type of the data.
