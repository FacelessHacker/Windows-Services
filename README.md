# Windows-Services
### Detailed explanation of Windows Services and how to create one.
### Case Study: Calc.exe 



##### What are Windows-Services?
Simply put, Windows-Services enables users to create Programs\Applications that runs in the background. A user can make a program start in the background and also stop or pause a program from running. For the effective functionality of the System, certain programs run in the background all time. Such services are what makes it easy to login to the system successfully. Background services can be accessed through the 'Services' Application on the system. Note that running applications in the background are called 'Services'. 


##### Open Services Through the Command Prompt

- Click on the windows icon + R on the keyboard to open the run window
- Enter 'services.msc' in the search box
- The Application will start
- Make sure you run it as Administrator


##### Open Services Through the Start button
- Click on the windows button on the keyboard or on the left side of the PC
- Type 'Services' in the search box
- Services App will appear, run as administrator & open the App.

On the Services App, background programs will appear. The user can click on any of the programs to make changes to them i.e., stop a running program, pause, or start.

##### Steps to Add a New Services using the Command Prompt (cmd)
- 


- Command Prompt will start
- Type c:\windows\microsoft.net\framework\v4. 0.30319\installutil.exe [your windows service path to exe]
- Press return and that's that!

##### Creating a Background Service Through the Start Icon

- Clicking on Start Icon
- 
