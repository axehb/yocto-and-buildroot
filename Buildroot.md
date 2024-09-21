# Buildroot guide

First we start by cloning Buildroot repo from github<br>
![](buildroot_evidence/cloning_repo_1.png)  
Inside this directory we can see raspeberry configuration  
![](buildroot_evidence/checking_for_boards_2.png)  
So we compile based on that board  
![](buildroot_evidence/selecting_raspberry_3.png)  
Then we can exectute the UI for extra tools that we may need  
![](buildroot_evidence/Executing_the_UI_4.png)  
Here let's say for example that we need open SSH and we add it  
![](buildroot_evidence/Selecting_openssh_as_a_module_example_5.png)  
We exit and we are asked automatically to save the configuration  
![](buildroot_evidence/save_configuration_and_make_the_file_6.png)  
After that we get our final image compiled with the name of sdcard_image  
And in this case we flashed it using the Raspberry Pi Imager.  
We can see Buildroot welcoming us.    
![](buildroot_evidence/Buildroot_login_7.jpg)  
Login as root and applying some disk usage commands  
![](buildroot_evidence/applying_commands_8.jpg)
