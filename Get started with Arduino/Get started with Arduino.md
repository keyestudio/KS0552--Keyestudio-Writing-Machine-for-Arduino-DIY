# Get started with Arduino

## 1. Windows System：           

### 1.1 Installing Arduino IDE
When you get control board, you need to download Arduino IDE and driver firstly.
You could download Arduino IDE from the official website:
https://www.arduino.cc/, click the SOFTWARE on the browse bar, click“DOWNLOADS” to enter download page, as shown below:
![Img](./media/img-20230927101210.png)
![Img](./media/img-20230927101219.png)

There are various versions of IDE for Arduino. Just download a version compatible with your system. Here we will show you how to download and install the windows version of Arduino IDE.
![Img](./media/img-20230927101243.png)

There are two versions of IDE for WINDOWS system. You can choose between the installer (.exe) and the Zip file. For installer, it can be directly downloaded, without the need of installing it manually while for Zip package, you will need to install the driver manually.
![Img](./media/img-20230927101255.png)

You just need to click JUST DOWNLOAD.

After the Arduino is downloaded, click“**I Agree**”to continue installing。
![Img](./media/img-20230927101314.png)
![Img](./media/img-20230927101318.png)

Click “**Next**”。
![Img](./media/img-20230927101400.png)

Then click “**Install**”。
![Img](./media/img-20230927101427.png)

If the following page appears, click “Install”。
![Img](./media/img-20230927101454.png)
![Img](./media/img-20230927101458.png)

### 1.2. Install the driver of CH340：
If the driver of CH340 is installed, just skip following steps.
If your system is Windows 10 or MacOS, the computer will automatically install driver.

If not，you need to install driver manually.

Connect the control board to computer with a USB cable.

Click “**Computer**”----- “**Properties**”----- “**Device Manager**”, as shown below:
![Img](./media/img-20230927101658.png)

Then right-click on the device and select the top menu option (**Update Driver Software...**) shown as the figure below.
![Img](./media/img-20230927101741.png)

Then it will be prompted to either“**Search Automatically forupdated driversoftware**” or“**Browse my computer for driver software**”. Shown as below. In this page, select “**Browse my computer for driver software**”.
![Img](./media/img-20230927101802.png)

After that, select the option to browse and navigate to the “drivers” folder (<span style="color: rgb(255, 76, 65);">**usb_ch341_3.1.2009.06 folder**</span>) of usb-ch341 installation.
![Img](./media/img-20230927102722.png)

Then check the serial port, as shown below：
![Img](./media/img-20230927102739.png)

### 1.3. Arduino IDE Setting：
![Img](./media/img-20230927102856.png)
A- Used to verify whether there is any compiling mistakes or not.
B- Used to upload the sketch to your Arduino board.
C- Used to create shortcut window of a new sketch.
D- Used to directly open an example sketch.
E- Used to save the sketch.
F- Used to send the serial data received from board to the serial monitor.

### 1.4. Start your program:
Click“<span style="color: rgb(255, 76, 65);">File</span>”<“<span style="color: rgb(255, 76, 65);">Examples</span>”<“<span style="color: rgb(255, 76, 65);">Basics</span>” <“<span style="color: rgb(255, 76, 65);">Blink</span>”
![Img](./media/img-20230927103024.png)
![Img](./media/img-20230927103029.png)

Select the correct board and serial port.
![Img](./media/img-20230927103040.png)

Click ![Img](./media/img-20230927103053.png) to upload the script
![Img](./media/img-20230927103103.png)

Then you can see the LED on the board flash.

## 2. Mac System:

### 2.1 Install Arduino IDE on MAC System

The installation instruction is as same as the chapter 1.1, as shown below:
![Img](./media/img-20230927103156.png)

### 2.2 Download the CH340 driver

https://fs.keyestudio.com/CH340-MAC

### 2.3 How to install the CH340 driver

Please refer to the following link:
https://wiki.keyestudio.com/Download_CH340_Driver_on_MAC_System

### 2.4 Setting Arduino IDE

The setting method is as same as the chapter 1.4 except from COM port, as shown below:
![Img](./media/img-20230927103314.png)


## 3. Burn the firmware of the writing machine

Import the libraries of the machine to the Arduino, as shown below:
![Img](./media/img-20230927103341.png)

Enter the Arduino: <span style="color: rgb(255, 76, 65);">Sketch</span> > <span style="color: rgb(255, 76, 65);">Include Library</span> > <span style="color: rgb(255, 76, 65);">Add .ZIP Library</span> 。
![Img](./media/img-20230927103421.png)

Find out the file package we provide and open it, as shown below：
![Img](./media/img-20230927103442.png)

Until this step, the installation is finished

Open the firmware code and program
![Img](./media/img-20230927103517.png)
![Img](./media/img-20230927103522.png)











