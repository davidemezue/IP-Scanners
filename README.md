# IP Scanners

## Lab Objective

Learn how to use IP Scanners for network reconnaissance.

## Lab Purpose

IP scanners are tools which scan and monitor your network. They are often used by administrators for discovering devices on a network as well as remotely managing these devices.

## Lab Tool

- Windows

## Lab Topology

You can use Windows for this lab.

## Lab Walkthrough

### Task 1: Downloading Advanced IP Scanner

We will be demonstrating how to use an IP scanner on a Windows machine in this lab.

To begin, download the following IP scanner:

https://www.advanced-ip-scanner.com/

### Task 2: Installing Advanced IP Scanner

Now, double-click the downloaded file and complete the installation in the order shown in the figures.

1. Select English, then click **OK**.
2. Select **Install**, then click **Next**.
3. Accept the agreement.
4. Click **Finish**.

### Task 3: Scanning the Network

This will scan our network and pick up on all devices connected to the network.

It will display information such as each device's IP address and MAC address.

Enter your subnet range in the space. If you do not know said range, simply hit the **Scan** button.

Then start the scan.

When the scan is complete, the nodes detected on the network will be listed together with their MAC and IP addresses.

### Task 4: Remotely Managing Network Devices

This tool can then be used to connect and remotely manage any of these devices.

To do this, simply select the device you would like to manage.

You will be asked to install another tool called Radmin, which will allow you to control the other devices on your network.

Click **Yes** and install it.

**Note:** To successfully control a device on your network, you will need to have a Radmin Server running on that device.

Now:

1. Right-click on the network.
2. Click **Radmin**.
3. Click **Full Control**.
4. Click **OK** to download Radmin Viewer.

There are a lot of useful functions admins can perform when taking control of a device on their network using this tool, such as:

- Taking full control.
- Read-only control.
- Connecting via Telnet.
- File transfer.
- Shutting down the device.
- Chatting via both text and voice.

This tool is useful for network administrators as it can both manage devices and pick up on any rogue devices present on their network.

### Task 5: Exploring Angry IP Scanner

IP scanners can also be installed on Linux.

The most popular of these is called Angry IP Scanner, or simply ipscan.

It is open source and provides the same functionality as the above IP Scanner.

It can be downloaded for Windows, Mac, and Linux from the following link:

https://angryip.org/

## Conclusion

This lab introduces IP scanning tools used for network reconnaissance and device discovery.

The exercises cover:

- Downloading and installing Advanced IP Scanner.
- Scanning a network to discover connected devices.
- Identifying devices through their IP and MAC addresses.
- Exploring remote device management using Radmin.
- Introducing Angry IP Scanner as an alternative available across multiple operating systems.

IP scanning is an important part of network administration and reconnaissance because it helps identify devices connected to a network.
