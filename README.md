# Download ROS
How to download ROS on Ubuntu
Download Virtualbox to your device to install Ubuntu from this link
https://www.virtualbox.org/wiki/Downloads
 
Download Ubuntu from https://ubuntu.com/download/desktop and then from virtualbox choose new and choose the type of operating system linux as shown in the picture
 

Choose the memory size, then click Next
 
Choose the create a virtual hard disk now, then click Create
 






Choose the VID, then click Next
 
Choose the Dynamically allocted, then click Next
 




Choose 30 GB, then click Create
 
Then choose setting and then choose storage and then locate the ubuntu you have loaded on your device 
 



Then open the system that you made and download the Ubuntu and select the language and then choose in the type of download Erase disk and install ubuntu and finally put your name and a special password in you for the operating system and then wait for it to bear and open with you as in the picture 













open the terminal and put the command line
Sudo apt update
Sudo apt upgrade
 










Putting the same command line as in the picture


sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'


sudo apt-key adv –keyserver 'hkp://keyserver.ubuntu.com:80' –recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
Sudo apt-get upgrade
 






Then put the command line to download ros
sudo apt-get install ros-desktop-full
 
 
References:
1-https://www.udemy.com/course/ros-basics-program-robots/learn/lecture/8892578#overview
2- http://wiki.ros.org/kinetic/Installation/Ubuntu





طريقة تحميل ROS  على Ubuntu
تحميل virtualbox على جهازك حتى تتمكن من تنصيب Ubuntu من هذا الرابط https://www.virtualbox.org/wiki/Downloads
 
قم بتنزيل  Ubuntu من الرابط  https://ubuntu.com/download/desktop  و بعد ذلك من virtualbox اختر new واختر نوع نظام التشغيل  linux كما هو موضح في الصورة ثم اضغط على التالي
 
اختر حجم الذاكرة ثم اضغط على التالي
 


اختر create a virtual hard disk now ثم اضغط انشاء
 




اختر VID ثم اضغط التالي
 
اختر Dynamically allocted ثم اضغط التالي
 




حدد حجم الملف 30 GB ثم اضغط انشاء 
 

ثم اختر setting وبعدها اختر storage ثم حدد الموقع لل  ubuntuالذي حملته على جهازك
 



بعدها افتح النظام الذي عملته ونزل الابنتو وحدد اللغه وبعدها اختر في نوع التنزيل Erase disk and install ubuntu و اخر شي ضع  اسمك و باسوورد خاص فيك للنظام التشغيل وبعدها تنتظر حتى يتحمل ويفتح معك كما في الصوره
 














افتح terminal ونضع الاوامر
Sudo apt update
Sudo apt upgrade
 











ونضع نفس اسطر الاوامر الموجوده  كما في الصوره
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

sudo apt-key adv –keyserver 'hkp://keyserver.ubuntu.com:80' –recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
Sudo apt-get upgrade
 







وبعدها تضع الامر لتنزيل ros
sudo apt-get install ros-desktop-full
 
 

