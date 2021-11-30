 

# IIS Server and Access Logging Setup

## IIS Server Setup

1.  Open Server Manager from Start menu.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/1.png)


2. Select “Add roles and features” on Server Manager Dashboard.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(2).png)


3. A wizard will open, click on next.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(3).png)


4. Click on next.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(4).png)


5. Again, click on next.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(5).png)

 
6. Select “Web Server(IIS)” in Server Roles.
 
![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(6).png)

7. Click on "Add Features"

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(7).png)

 
8. Click on next.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(8).png)


9. Click on next.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(9).png)


10. In Role Services, select all features under “Common HTTP features”, “Health and Diagnostics” and “Performance”. 

 ![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(10).png)


11. Install.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(11).png)


12. Wait for installation to complete.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(12).png)


13. After Installation, close the wizard.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(13).png)


14. Navigate to Server Manager Dashboard, IIS Web Server is installed and can be seen in the left side bar.
 
![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(14).png)


15. Click on IIS. Your server will be listed under "SERVERS".

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(15).png)

 
16. Right click on your server, and select “Start Performance Counters”.
 
![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(16).png)

### IIS Access Logging Setup

1. Right click on your server again, and select "Internet Information Services(IIS)".

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(17).png)

 
2. Navigate to your web site in left hand side menu, and select it.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(18).png)


3. Double click on "Logging Option".

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(19).png)

 
4. Click on “Select Fields…”.
 
![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(20).png)


5. Select all fields.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(21).png)

 
6. After selecting all fields, click on “Ok”.

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(22).png)


7. Click on "Apply" in the right pane under "Actions".

![img](https://github.com/gaurav-dot-chaudhary/sampleproject/blob/master/IIS/Screenshot%20(23).png)

 

IIS Web server setup is complete with access logging.
