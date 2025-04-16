# powershell-tools
**How to Use:**

1. **Save the Script**: Copy the above code into a file with a `.ps1` extension (e.g., `MenuTools.ps1`).
2. **Run in PowerShell**:
   - Open PowerShell.
   - Navigate to the script's directory: `cd "Path\To\Script"`
   - Execute the script: `.\MenuTools.ps1`
3. **Interact with the Menu**:
   - Enter the number of your chosen option (1 for IP, 2 for Network, 3 for Local).
   - Follow the sub-menu prompts for each tool.
   - To exit the script, currently you must return to the main menu and then you can simply close the PowerShell window or add an exit option by modifying the script (e.g., adding a `4. Exit` option in each menu and handling it appropriately).

**Tools Overview by Menu Option:**

### 1. **IP**
- **View Current IP Config**: Displays current network interface configurations.
- **Renew DHCP Lease**: Releases and renews the DHCP lease for the primary interface.

### 2. **Network**
- **List All Network Connections**: Shows all network connection profiles.
- **Check Internet Connectivity**: Tests connectivity by pinging Google.

### 3. **Local**
- **System Overview**: Provides an overview of the OS and computer system.
- **Processor and RAM Info**: Displays detailed processor information and total RAM.
