# ubuntuism
Begin your journey with Ubuntu here. This is a tutorial about **Dual Boot of Ubuntu with Windows**

### Part 1 - Windows
**1. Open Disk Management in Windows to partition your disk**
<img src="./images/1_Windows/Step_1.png" width="600" text="Step 1"> 

**2. Allot space for Ubuntu Installation** </br>
Select the partition that you want to give for Ubuntu by shrinking the Windows Disk Volume. 
<img src="./images/1_Windows/Step_2.0.jpg" width="300" text="Step 2.0"></br>

Specify the amount of space that you want to allot for Ubuntu.
<img src="./images/1_Windows/Step_2.1.png" width="500" text="Step 2.1"></br>

Make a suitable allotment based on your requirement. Ensure you have at least 35 GB of free storage space for Ubuntu 
<img src="./images/1_Windows/Step_2.2.PNG" width="500" text="Step 2.2"></br>

 My Disk Partition is ready. In my 1TB harddisk I am using 512GB for Ubuntu(Unallotted Partition) and the rest for Windows. 
<img src="./images/1_Windows/Step_2.3.PNG" width="900" text="Step 2.3"></br>

**3. Download the Image and create a Bootable USB** </br>
Download the Ubuntu Image from the offical website</br>
Link : http://old-releases.ubuntu.com/releases/18.04.3/ubuntu-18.04-desktop-amd64.iso</br>
Note: While installing I faced certain issues with 18.04.4, thus, I used 18.04.3 version during my installation.</br>

To flash the image in our system, lets create a bootable pendrive image</br>
Download Rufus or Etcher to create a bootable USB Image </br>
Link: https://rufus.ie/   (or) 
Link: https://www.balena.io/etcher/	</br>
<img src="./images/1_Windows/Step_3.png" width="400" text="Step 3"> 
</br>(or)</br>
<img src="./images/1_Windows/Step_3.gif" width="400" text="Step 3">  

<ul>
  <li> Insert a formatted pendrive with 4GB space available.</br> </li>
  <li> Select the location of downloaded Ubuntu image and the pendrive path.</br> </li>
  <li> Flash the image using any of the 2 softwares. </br> </li>
</ul>

</br>
&nbsp; We have successfully completed our pre-requisites. Lets jump into our main course. So you both, Refresh and restart!! :-P 
</br>

<ul>
Refer : 
  <li> https://support.microsoft.com/en-in/help/17418/windows-7-create-format-hard-disk-partition </br> </li>
  <li> https://releases.ubuntu.com/18.04.3/ </br> </li>
</ul>
</br>
</br>

### Part 2 - Ubuntu Installation

**1. Changing the boot option**  </br>
Power ON the system and immediately press the boot option button F12 continously(in most of the PCs, check it online). </br>
The system enters the boot menu. Select the "USB Boot" option(Sandisk in my case) </br>
<img src="./images/2_Linux_Install/Step_1.jpg" width="600" text="Step 1"> 

**2. GRUB Menu** </br>
In the Grub Menu select "Install Ubuntu" option</br> 
<img src="./images/2_Linux_Install/Step_2.jpg" width="600" text="Step 2"></br>

**3. Select Language** </br>
<img src="./images/2_Linux_Install/Step_3.jpg" width="600" text="Step 3"></br>

**4. Select Keyboard Layout** </br>
<img src="./images/2_Linux_Install/Step_4.jpg" width="600" text="Step 4"></br>

**5. Select Wireless network settings** </br>
<img src="./images/2_Linux_Install/Step_5.jpg" width="600" text="Step 5"></br>

**6. Select the Installation option** </br>
Select the updates and software that you need. You can proceed with Normal Installation, omit 3rd party softwares and turn off secure boot.</br> 
<img src="./images/2_Linux_Install/Step_6.jpg" width="600" text="Step 6"></br>

**7. Configure Ubuntu Partition** </br>
<img src="./images/2_Linux_Install/Step_7.0.jpg" width="600" text="Step 7"></br>

<ul>
From your free space shown in the list create 4 partion spaces
  <li> /boot (grub and boot)</br> </li>
  <li> / (root - superuser) </br> </li>
  <li> /home (the user) </br> </li>
  <li> /swap (swap space) </br> </li>
</ul>
<img src="./images/2_Linux_Install/Step_7.jpg" width="900" text="Step 7"></br>

<ul>
The recommended partition for a PC with 100 GB Ubuntu space
  <li> swap - 2 times the RAM size (For a 4GB RAM, swap is 8GB) </br> </li>
  <li> boot - 1GB  </br> </li>
  <li> root - 25GB </br> </li>
  <li> home - 66GB </br> </li>
</ul>

Select "Boot Loader Installation Space" as /dev/sda </br>
My Ubuntu Partition Space with format option selected </br>
<img src="./images/2_Linux_Install/Step_7.5.jpg" width="600" text="Step 7"></br>

You have completed 7.5(Steps) just a few more.</br>
You should be getting a confirmation page about your partition. </br>
<img src="./images/2_Linux_Install/Step_7.6.jpg" width="600" text="Step 7"></br>

**8. Take Rest - Let it install** </br>
Proceed with it and your installations would be successfully completed (hopefully :-P)
<img src="./images/2_Linux_Install/Step_8.jpg" width="600" text="Step 8"></br>

Note : In some cases, you may need to update your BIOS. Check with the Manufacturer. 
<img src="./images/2_Linux_Install/Note_1.jpg" width="600" text="Note_1"></br></br>

I too faced errors during my installation and have successfully fixed them. Happy Learning :-P 
