# MyDemoApp_MSI
demo code to generate msi file for installation

# Inorder to compile and run the wix file

candle -out MyDemoApp.wixobj MyDemoApp.wxs

light -b ./ -out "C:\Users\sysadmin\Desktop\MyDemoApp\output\demo.msi" MyDemoApp.wixobj

# MyDemoApp.wixobj can be deleted as it will be auto generated after we run the candle command.
# WiX version: 2.0.4751

Change the version of the Wix as per requirement.
