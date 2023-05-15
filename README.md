# A Step-by-Step Guide to Manually Configuring SSH in NapsternetV Application

## Introduction:

NapsternetV is a versatile network tunneling application that allows you to create secure connections and bypass restrictions on your network. It provides encrypted communication channels for secure remote access and data transfer. In this tutorial, we will walk you through the process of manually configuring an SSH profile in NapsternetV.

## Prerequisites:

1. NapsternetV application installed on your device.
2. An SSH server with the necessary credentials (IP address, port, username, and password).

### Step 1: Launch NapsternetV

Open the NapsternetV application on your device and go to the **Configs** page.

If you haven't installed it yet, you can find it in your device's app store or download it from the official NapsternetV website.

### Step 2: Create a New Profile

Tap on the **"+"** or "New Profile" button to create a new profile in NapsternetV.

Tap on the **“Add config manually”** option.

Tap on the **“SSH Config”** option.

### Step 3: Configure the General Settings

In the profile settings, you will see various options. Fill in the following details:

- **Protocol** Type: Select **"SSH-Direct"** from the available options.
- **Remark:** Give your profile a name in this field (e.g., my-tunnel-name) to easily identify it.
- **SSH Host**: Enter the IP address or domain name of your SSH server.
- **SSH Port**: Specify the port number associated with your SSH server.
- **Udpgw Port**: Leave this option as is. The default port is 7300.
- **SSH Username**: Provide the username associated with your SSH server.
- **SSH Password**: Enter the password for authentication.

### Step 4: Save and Activate the Profile

Once you've configured the SSH settings, tap the **"Save"** button to save your profile. You will be redirected to the main screen of NapsternetV. **To activate the profile, tap on the profile name you just created.**

### Step 5: Connect and Start Tunneling

After activating the profile, go to the **Home** page of the application. You will see a play button or "Connect" option. Tap on it to initiate the SSH connection and start tunneling your network traffic through the SSH server. Once connected, you should see a "Connected" or "Tunneling" status in the NapsternetV interface.

### Step 6: Verify the Connection

To ensure that your SSH tunnel is functioning correctly, you can visit websites or use network-dependent applications to confirm that the traffic is being routed through the SSH server. Additionally, you can check the logs or connection status within NapsternetV for any errors or warnings.
