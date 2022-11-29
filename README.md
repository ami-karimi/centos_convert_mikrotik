** Convert Centos 7 To Mikrotik 7.5 **

# Before Instalation

run Comment on Terminal :

1. **yum install wget unzip nano  curl**
2. check Your Interface Name By Run  Command:  **ip r**
3. After Check Your Check your server disk name by Command: **lsblk**


Mikrotik Version: 7.5


**After Check DiskName Run Command:**

For **SDA**:


bash <(curl -Ls https://raw.githubusercontent.com/ami-karimi/centos_convert_mikrotik/master/convert_sda.sh)



For **VDA**:


bash <(curl -Ls https://raw.githubusercontent.com/ami-karimi/centos_convert_mikrotik/master/convert_vda.sh)


# after Instalation

**Install WinBox Or Use Your Ip Address For Login To Mikrotik**

username: **admin**
password: **admin**

If Not Correct  User Name Or Password Error

Empty PassWordBox :)


Enjoy;
