Fork from PaulStovell

Download of the latest AppVeyor build: [**download (.exe)**](https://ci.appveyor.com/api/buildjobs/v1xy9wg0pi50372a/artifacts/source%2FServiceBouncer%2Fbin%2FRelease%2FServiceBouncer.exe)

As a developer building Windows Services, the workflow of constantly stopping and starting services can be a bit annoying, especially if your solution consists of multiple services. **ServiceBouncer** is a simple tool that helps to streamline this workflow. 



The tool shows a data grid for the services, and their status. Since it's a grid, you can easily select multiple services. You can then start or stop them. You can also filter the services shown, so that you don't accidentally stop the wrong one. There's even a button to delete services you no longer need. 

![ServiceBouncer main window - stop, start, delete and filter services](https://res.cloudinary.com/octopusdeploy/image/upload/v1428816191/2015-04-12_15_22_48-Untitled_-_Notepad_l3a2kf.png)

The window title tells you the status of the services, so you can quickly tell if your service is running without switching windows:

![ServiceBouncer window title](https://res.cloudinary.com/octopusdeploy/image/upload/v1428624736/2015-04-10_10_11_33-_nfnnn1.png)

