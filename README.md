# Windows RDP Setup with RustDesk

This guide will walk you through setting up a Windows RDP connection using RustDesk.

## Requirements
- Windows operating system.
- RustDesk installed on your system.
- A stable internet connection.

## Steps to Connect via RustDesk

1. **Download RustDesk**  
   Visit the official RustDesk release page to download the latest version of RustDesk:  
   [RustDesk v1.3.7 Release](https://github.com/rustdesk/rustdesk/releases/tag/1.3.7)

2. **Run the Workflow**  
   - Go to [Actions] in the repository.
   - Look for the **Windows - RustDesk** workflow.
   - Click on it, then click on the yellow **"Start Building..."** button to begin the build process.

3. **Wait for the Build to Complete**  
   - Once the build starts, wait for it to finish. This may take a few minutes.
   - After the build process completes, the system will automatically log you into RustDesk.

4. **Retrieve Your ID and Password**  
   - After logging in, you will see an ID and password displayed in the RustDesk interface.
   - **Copy the ID and Password**.

5. **Connect via RustDesk**  
   - On the RustDesk client, enter the **ID** and **Password** you copied earlier.
   - Click "Connect" to start your RDP session.

Once connected, you can start using your Windows desktop remotely via RustDesk!

## Troubleshooting

If you encounter any issues during the process:
- Ensure RustDesk is installed correctly and the version is up-to-date.
- Double-check that you copied the correct ID and password.
- Make sure your firewall settings are not blocking RustDesk's connection.

For more help, visit the [RustDesk documentation](https://rustdesk.com/docs).
