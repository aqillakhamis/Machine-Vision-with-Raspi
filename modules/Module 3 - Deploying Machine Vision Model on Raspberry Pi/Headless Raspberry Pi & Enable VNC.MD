## Step 1: Find the Raspberry Pi's IP Address 

1. Find your Raspberry Pi IP address. 

* For Windows: Open `command prompt`. In your command prompt: 

    ```
    ping <Raspi HOSTNAME> -4
    ```

* For MacOS: Open `terminal`. In your terminal:

    ```
    ping <raspi HOSTNAME>.local
    ```

2. Make sure your laptop connected with the same network with the one you use in the **Configure Wireless LAN**. 

## Step 2: Access Your Raspberry Pi via SSH

1. On your laptop, open a terminal (macOS) or Command Prompt (Windows)

2. SSH into the Raspberry Pi by type the following command, replacing `<IP_ADDRESS>` with the actual IP address of your Raspberry Pi: 

    ```
    ssh pi@<IP_ADDRESS>
    ```

3. The first time you connect, you'll see a message asking if you want to continue. Type `yes` and press `enter`. 

4. Enter the password the one you have set in Step 4 **Set Username and Password**. 

Now you're logged into your Raspberry Pi via SSH! 🎉🥳

## Step 3: Enable VNC in Raspberry Pi

We will use Real VNC Viewer for our Raspberry Pi User Interface (UI). In your terminal/command prompt, type:

```
sudo raspi-config
```

Go to interface option > VNC > select `enable`