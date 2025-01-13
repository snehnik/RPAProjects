Current version 1.10

Version 1.20 beta

Added support for background processes. Change project settings to "support background" in order for the process to run background. Changed performer/dispatcher to a switch in order to support further run-modes. 'OBS'-module must not be activated if running background

Version 1.10
It's now posible to start the proces with 3 different values for in_DispatcherOrPerformer ("Dispatcher", "Performer", "NoDispatcher")

Version 1.03
PrintConfig changed to PrintDictionary. Can now be used for printing any dictionary.
In dispatcher the dtBulkItem set with a default blank value to avoid throw at the first time run before declaring it.
New permanent test-file to clear/reset queue. Clean up the queue by setting all 'in progress' to failed and deleting 'new' items.
All invoke activities calling L-invokes from the Framework folder are renamed like 'L - Framework\NameOfFile'.

Version 1.02
Bug fix KillAllProcesses
Bug fix CloseAllApplication
Add Main close all not needed programs
Change Dispatcher close all programs in use instead of not needed (moved to Main)

Version 1.01
Bug fix print config




