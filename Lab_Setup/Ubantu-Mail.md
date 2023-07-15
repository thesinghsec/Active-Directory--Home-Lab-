# Creating Virtual UbuntuMail:

Download: **[Ubuntu](https://ubuntu.com/download/desktop)**

Reference: [Article for setting up UbuntuMail](https://www.hostinger.co.uk/tutorials/how-to-install-and-setup-mail-server-on-ubuntu/)

-  **Steps to create a virtual machine:**

    - Open Virtual Box.

    - Click on create a new virtual machine.

    - Follow the prompts to name your virtual machine and choose the desired operating system.

    - Allocate the desired amount of RAM for the virtual machine.

    - Specify the size and location for the virtual hard disk.
   
    - Start the virtual machine and proceed with the installation of the chosen operating system.

![img.png](Images/ub-images/img.png)

Select the "Install Ubuntu" option from the installation menu. Please note that the exact wording may vary slightly depending on the specific version or edition of Ubuntu you are using.

![img_5.png](Images/ub-images/img_5.png)

Proceed with the default keyboard layout selection. If the defaults are compatible with your keyboard, simply click on the "Continue" button to proceed with the installation process.

![img_6.png](Images/ub-images/img_6.png)

By default, the installation type is set to "Normal installation," which is the recommended option. 

![img_7.png](Images/ub-images/img_7.png)

Click on the "Install Now" button to initiate the installation process. Please note that the "Erase disk" option will only affect the virtual machine's disk within VirtualBox, and it will not impact any system files or data outside of the virtual environment. You can proceed with the installation without concern for your host system's files.

![img_4.png](Images/ub-images/img_4.png)

Click on the "Continue" button to proceed with the installation process. You will be prompted to confirm and write the changes to the disk. This step is necessary to initiate the installation of Ubuntu on the virtual machine's disk.

![img_8.png](Images/ub-images/img_8.png)

Select your location from the options provided to set the correct time zone for your virtual machine. 

![img_9.png](Images/ub-images/img_9.png)

Choose a name for your computer and set a password to secure login info.

![img_10.png](Images/ub-images/img_10.png)

Please wait patiently for the installation process to complete. The duration of the installation may vary depending on the system specifications and the selected installation options.

![img_11.png](Images/ub-images/img_11.png)

After the installation process is complete, it is recommended to reboot your virtual machine. Rebooting will finalize the installation and ensure that all the necessary configurations are applied.

![img_12.png](Images/ub-images/img_12.png)

Congratulations! You have successfully completed the installation process for Ubuntu as a virtual machine.

![img_13.png](Images/ub-images/img_13.png)

# Network Settings:

 Configure network settings for the "ubuntumail" virtual machine, follow these steps:

1. Select the "ubuntumail" virtual machine.
    
2. Click on "Settings" to access the VM settings.
   
3. Navigate to the "Network" section.
    
4. Under "Adapter 1," choose "NAT Network" from the dropdown menu.
    
5. Select the name "External" from the available options.

![img_14.png](Images/ub-images/img_14.png)

# Configure Network Adapter:

Click on "Settings" > "Wired Connect" > "Wired settings"

![img_15.png](Images/ub-images/img_15.png)

Click "Setting" icon.

![img_16.png](Images/ub-images/img_16.png)

In the network settings, locate and click on "IPv4". Then, disable the automatic DNS configuration and manually enter the DNS address as "8.8.8.8", Click Apply.

![img_17.png](Images/ub-images/img_17.png)

Please make sure that your network settings match the configuration displayed in the provided image. While the IPv4 address may vary, ensure that the highlighted settings remain the same. Click Apply.

![img_18.png](Images/ub-images/img_18.png)

 Disable and then re-enable the wired connection.
 
Open the terminal application on your Ubuntu virtual machine and enter the command "ping google.com". This command will initiate a ping request to the Google website and display the response time and connectivity status between your virtual machine and the Google server.

![img_19.png](Images/ub-images/img_19.png)

 You have successfully completed the installation of Ubuntu as a virtual machine, configured network settings, and performed additional steps to ensure connectivity.