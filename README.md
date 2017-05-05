# Quali-ZT-20X6NB
CloudShell Shell for controlling up to (4) ZT-20X6NB Devices.

The ZT20X6NB shell supports the ZT-20X6NB device within the CloudShell interface. It allows the user to interact with up to 4 ZT-20X6NB devices from a single shell. The full, standard control command set is modeled and implemented, allowing same level of control as the device’s GUI program. However, CloudShell gives you the additional ability to send commands simultaneously to 1, 2, 3 or 4 devices, minimizing the delay between different ZT boxes receiving commands.

## CloudShell Version 6.x

### Installation

1. Download the ZT-20X6NB_Cl6.x.zip file to your computer
2. Extract The Files.
3. Import The driver Through CloudShell portal.
4. Create a new Resource Model in "Resource Management Client"
   - Create 4 attributes to add to your model:
      DeviceIP_1, DeviceIP_2, DeviceIP_3, DeviceIP_4
   - assign the attributes to your model.
   - Save Changes and refresh.
   
5. In CloudShell Portal
   - Edit the driver
   - assign the model you created to the driver models list
   - apply and save.
   
6. Activate the driver.
7. Reserve the resource in the sandbox.
8. Set the IP addresses on the attribute panel.
9. Save changes.
10. The resource can now be used in the environment

### Further Instructions

On procedure how to use the shell and more detailed installation instructions, please see the attached ZT-20X6NB Cloudshell guide for CloudShell version 6.x


## CloudShell Version 7.1


### Installation

1. Download the ZT-20X6NB.zip file to your computer
2. Login to your CloudShell Portal as an administrator
3. Click on “admin” – “import package”
4. Locate the ZT-20X6NB.zip file in the file browser and click “open.”
5. Once the package is imported you can create a resource from it and use it in your CloudShell environment

### CREATING A ZT-20X6NB RESOURCE IN CLOUDSHELL

1. Login to your CloudShell portal as administrator
2. Go to the “Inventory” tab
3. Click “Add New”:
4. From the list select the ZT-20X6NB resource
5. Enter the name you want to use for the resource. The resource will be named ZT-20X6NB by default. You may wish to assign it     another name depending on your requirements.
6. For the “Address” field, enter “N/A” (this field is not used but cannot be left blank in order for inventory discovery to work)
7. Click “Create”
8. Enter the IP address for each ZT device you want to control with this Shell. Minimum of 1 IP is required. Use Mini-Circuits’ GUI program to find the IP address of your unit. Refer to the ZT-20X6NB User’s Manual for additional guidance on Ethernet Configuration.
9. Click “Start Discovery”
10. The resource will be added to the inventory tab. All connected ZT devices will have their serial number reported in the corresponding attribute
11. You may now use the resource in your environment

### Further Instructions

On procedure how to use the shell and more detailed installation instructions, please see the attached ZT-20X6NB Cloudshell guide.
