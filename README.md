# SmartTvHelloWorld

A hello world app for Samsung Smart TV 2014 platform.

## Environment Setup

1. You will need [VirtualBox](https://www.virtualbox.org/) and [Java](http://java.com/en/download/). I have VirtualBox 4.3.12 and Java 1.8 on OSX Yosemite
2. Get the Samsung flavoured Ecplise IDE and the Smart TV emulator VM from http://www.samsungdforum.com/devtools/sdkdownload
3. You may need to change the shared folder settings for the Smart TV emulator VM (VirtualBox > Smart_TV > Settings > Shared Folders) to folders that actually exist on your machine - keep the same name but change the path (I had to delete then re-create the entries because editing them in-place caused VirtualBox to hang).
4. Point eclipse to the right virtual machine (Eclipse > Preferences > Samsung Smart TV > Emulator > Emulator Machine Name)

You should now be able to Run the project as "Samsung Smart TV emulator"


