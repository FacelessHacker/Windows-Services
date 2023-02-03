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

![UI Image](https://github.com/FacelessHacker/Windows-Services/blob/main/Screenshot%20(44).png)

##### Steps to Add a New Services using the Command Prompt (cmd)

To Access The Command Prompt 
  - Click on the windows button on the keyboard or on the left side of the PC
  - Type 'Command Prompt' in the search box
  - Run as Administrator
  - Command Prompt will start
  
Adding the New Services

  - Type the command below in the prompt

  ```
  sc create "Rahmat" binPath= "C:\Windows\System32\Calc.exe"
  ```
  
  - Rahmat= name to give to the service $ "C:\Windows\System32\Calc.exe" = The full path of the Servi to create
  
  - Alas!!! Service created succesfully!
  
  ![UI Image](https://github.com/FacelessHacker/Windows-Services/blob/main/Screenshot%20(41).png)
  
  - Press return and that's that!
  
Check 'Services' For the Program Added & Set it as You Like

  - Look for the service name 'Rahmat'
  - Right click on it, a box will appear.
  - Chose properties and right click on it.
  - A big Box will appea
  - Read and choose the instructions as wish
  
  ![UI Image](https://github.com/FacelessHacker/Windows-Services/blob/main/Screenshot%20(43).png)
  
  ### A NEW SERVICE has been SUCCESSFULLY CREATED!!!
  
