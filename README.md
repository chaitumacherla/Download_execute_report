In this project, we are splitting the project into small number of sections. Each section is explained with example.

In first section, we create a repo which execute the system commands and report the output to our email. Here we try to know the passwords of the computer that the target computer is connected to.

Command1 : netsh wlan show profile   #It lists all the wifi networks that are connected to the target.
Command2 : netsh wlan show profile <networkname> key=clear    #It gives the passowrd of the particular network.

In second section, we create a repo which can download any file, image, pdf, exe on target computer. Here, we try to download the image.

In last section, we combine all these functions to downlaod any file, execute the system commands and report it to the mail. Here we have a program called laZagne which steals the stored passwords from the remote computer. Here, we try to download teh laZagne in target computer and execute the system command and report the output to our email.

Command : laZagne.exe all #It gives the passwords stored in the target computer. 