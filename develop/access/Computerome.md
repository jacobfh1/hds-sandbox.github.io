---
layout: page
title: Computerome
parent: Access
has_children: false
nav_order: 1
hide:
  - footer
  - toc
---

# Accessing the Sandbox on Computerome

<b>We do not currently support independent use of Sandbox materials on Computerome</b>. Access is supported via courses collaborating with the Sandbox and run on Computerome's [Course Platform](https://computerome.dk/solutions/course-platform). Check [here](https://hds-sandbox.github.io/access/index.html) for more info. 

*The below instructions are provided as reference for course participants.*

To set up a user account on Computerome, you will need to provide administrators with your name, email address, and phone number for two-factor authentication. Once approved as a user, you will receive your username and server address (URL) by email, and you will receive an initial course-platform password by text.

On Computerome, the Sandbox environment is deployed as a virtual machine with a Linux desktop as user interface. This environment can be accessed through VMware Horizon using two different methods: (A) a desktop client (which you install on your computer) or (B) a web-based client (for those without install privileges on their computer). Please follow the appropriate instructions (A versus B) depending on your access preference.

!!! note "Sign-In Instructions"
    1. On FIRST login, enter the provided server address (URL) in a browser window to access the environment using your provided credentials. The URL will take you to a VMware Horizon access portal where you can
      *  (A) choose to install the desktop client (left: 'Install VMware Horizon Client'). You will then open this client for all subsequent logins instead of using the server address, and can login starting from step 2. 
      *  (B) access the environment via browser (right: 'VMware Horizon HTML Access'). You will always use the server address in your browswer to access this entry point if this is your chosen method of access.

    2. Select the cloud icon
      *  (A) which is linked to the server URL. This option appears when you have successfully installed and opened the VMware Horizon client.
      *  (B) which is linked to the Sandbox course. This option appears after you have selected VMware Horizon HTML Access.

    3. Enter your username and your course-platform password. 
      *  On the first sign-in, this will be the course-platform password texted to you. You will then be prompted to create your own permanent password to replace this password which you will use for all future sign-ins.

    4. When prompted, enter the one-time password texted to you from DTU (NOT the same password as the course-platform password).
      *  (A) If it is your first login / you logged off at last access, press any key when greeted with the blue time status screen. This will allow you to select your own user account in a dialog box.

    5. Sign-in using your course-platform password again after choosing the correct language for the environment in the upper right corner of the screen (this is important for the keyboard and typing your password). Danish (the da option) is default, so those with English keyboards will need to switch to English (the en option) at every login.

    6. Congratulations, you have entered the Sandbox environment. Relevant links for courses should be present on your desktop.


!!! warning "Exit Instructions"
    To exit the environment, you have two options with different outcomes. You can log off and kill all running processes, or you can disconnect and your processes will continue running.  "Power off" is disabled for users as this will shut down your virtual machine, local settings and user files may be lost, and the virtual machine will need to be manually restarted for your account. 

    1. To exit and kill all running processes, select the power icon in the upper right corner, then select your name and choose "log off" in the pop up window.
    2. To exit and preserve running processes,
        *  (A) hover at the top of the screen for a few seconds until your VMware Client menu is accessible, choose "Connection", and select "Disconnect".
        *  (B) close the browser tab where you are accessing the Sandbox environment.
