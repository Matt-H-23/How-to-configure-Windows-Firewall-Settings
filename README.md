# How-to-configure-Windows-Firewall-Settings 🏠
-This lab illustrates a basic **Firewall Configuration Setting** for an AD Server
### Step 1: Configuring Windows FireWall Settings
**What's an AD Server, without protecting it, let's look at how to configure firewall settings for the AD Domain Controller** (Basic)
- Right click on **Domain Controller** and select **Create New GPO and Link it here** and name it **FireWall Rules**
-Follow this path **Computer Configuration** -> **Policies** -> **Windows Settings** -> **Security Settings** -> **Windows Defender FireWall with Advanced Security** -> **Windows Defender FireWall with Advanced Security** -> Right click on **Inbound Rules** and select **New Rule**
![Loom Screenshot 2025-06-06 at 08 57 02](https://github.com/user-attachments/assets/b4d32de0-7452-45d9-b5d2-24800aa3f278)
### Step 2:
- For the **Rule Type** select **Custom** -> **Program Type** can be left alone, on the **Protocol and Ports** tab for **Protocol Type** select **ICMPv4 -> Click **Next** until you get to the **Name** tab
![Loom Screenshot 2025-06-06 at 08 57 44](https://github.com/user-attachments/assets/e05e1e43-828a-436b-928d-611a2473b77f)
### Step 3:
- And Simply name it **Block ICMPv4** and hit **Finish**
![Loom Screenshot 2025-06-06 at 08 58 40](https://github.com/user-attachments/assets/8ae6b862-472c-4a09-a8c7-8749cc3326c9)
### Congrats You've Configured Your First(Basic) AD Server, Now let's See It In Action!!

## Demo Video🎥
[Firewall config video](https://www.loom.com/share/0ccebea9d8b94d6c816a7934ee133fa1?sid=43d3af55-7b4e-4849-aa28-82fd7ad95505)
