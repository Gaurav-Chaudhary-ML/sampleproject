 

# IIS Server and Access Logging Setup

## IIS Server Setup

1.  Open Server Manager from Start menu.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image002.jpg)


2. Select “Add roles and features” on Server Manager Dashboard.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image004.jpg)


3. A wizard will open, click on next.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image006.jpg)


4. Click on next.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image008.jpg)


5. Again, click on next.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image010.jpg)

 
6. Select “Web Server(IIS)” in Server Roles.
 
![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image012.jpg) |

7. Click on "Add Features"

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image014.jpg)

 
8. Click on next.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image016.jpg)


9. Click on next.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image018.jpg)


10. In Role Services, select all features under “Common HTTP features”, “Health and Diagnostics” and “Performance”. 

 ![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image020.jpg)


11. Install.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image022.jpg)


12. Wait for installation to complete.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image024.jpg)


13. After Installation, close the wizard.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image026.jpg)


14. Navigate to Server Manager Dashboard, IIS Web Server is installed and can be seen in the left side bar.
 
![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image028.jpg)


15. Click on IIS. Your server will be listed under "SERVERS".

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image030.jpg)

 
16. Right click on your server, and select “Start Performance Counters”.
 
![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image032.jpg)

### IIS Access Logging Setup

1. Right click on your server again, and select "Internet Information Services(IIS)".

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image034.jpg)

 
2. Navigate to your web site in left hand side menu, and select it.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image036.jpg)


3. Double click on "Logging Option".

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image038.jpg)

 
4. Click on “Select Fields…”.
 
![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image040.jpg)


5. Select all fields.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image042.jpg)

 
6. After selecting all fields, click on “Ok”.

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image044.jpg)


7. Click on "Apply" in the right pane under "Actions".

![img](file:///C:/Users/Gaurav%20Chaudhary/AppData/Local/Packages/oice_16_974fa576_32c1d314_fd3/AC/Temp/msohtmlclip1/01/clip_image046.jpg)

 

IIS Web server setup is complete with access logging.
