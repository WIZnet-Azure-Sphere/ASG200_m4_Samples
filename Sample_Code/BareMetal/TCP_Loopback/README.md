# ASG200 M4 real-time application sample: TCP Loopback

### Description

Sample application using TCP Loopback(Server/Client) over W5500 SPI.

* Create a TCP server socket using the and wait for a connection to the configured port.
* When data is sent by establishing a connection, you can check the received data by loopback.


## Build and Run the Application

The application can be run and developed with Visual Studio and Visual Studio Code.

### Run with Visual Studio

Follow these steps to build and run the application with Visual Studio:

1. Start Visual Studio, From the File menu, select `Open` > `Folder` and navigate to the current sample path, `TCP_Loopback`.

2. From the Select Startup Item menu, on the tool bar, select `GDB Debugger (RTCore)`.


<img src="https://github.com/WIZnet-Azure-Sphere/ASG200_App/blob/master/Docs/references/visual-studio-select-gdb-debugger-rt.png?raw=true"/>

3. Click `Build` > `Build All` to build the project


<img src="https://github.com/WIZnet-Azure-Sphere/ASG200_App/blob/master/Docs/references/visual-studio-build-the-project.png?raw=true">

4. Press F5 to start the application with debugging.


### Run with Visual Studio Code

Follow these steps to build and run the application with Visual Studio Code:

1. Open `TCP_Loopback` folder.

<img src="https://github.com/WIZnet-Azure-Sphere/ASG200_App/blob/master/Docs/references/visual-studio-code-open-project-folder.png?raw=true">


2. Press F7 to build the project

3. Press F5 to start the application with debugging
