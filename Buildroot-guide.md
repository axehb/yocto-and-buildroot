# Buildroot guide

First we start by cloning Buildroot repo from github.<br><br>
![](buildroot_evidence/cloning_repo_1.png)<br><br><br>
Inside this directory we can see raspeberry configuration.<br><br>
![](buildroot_evidence/checking_for_boards_2.png)<br><br><br>
So we compile based on that board.<br><br>
![](buildroot_evidence/selecting_raspberry_3.png)<br><br><br>
Then we can exectute the UI for extra tools that we may need.<br><br>
![](buildroot_evidence/Executing_the_UI_4.png)<br><br><br>
Here let's say for example that we need open SSH and we add it.<br><br>
![](buildroot_evidence/Selecting_openssh_as_a_module_example_5.png)<br><br><br>
We exit and we are asked automatically to save the configuration.<br><br>
![](buildroot_evidence/save_configuration_and_make_the_file_6.png)<br><br><br>
After that we get our final image compiled with the name of sdcard_image.  
And in this case we flashed it using the Raspberry Pi Imager.  
We can see Buildroot welcoming us.<br><br>
![](buildroot_evidence/Buildroot_login_7.jpg)<br><br><br>
Login as root and applying some disk usage commands.<br><br>
![](buildroot_evidence/applying_commands_8.jpg)
