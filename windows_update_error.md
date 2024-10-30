# Window10 configuration problems
##  Windows Update Error

## Steps to Resolve:
1. **Run the Windows Update Troubleshooter**
   - Navigate to Settings > Update & Security > Troubleshoot > Additional troubleshooters.
   - Run the "Windows Update" troubleshooter.

2. **Check Disk for Errors**
   - Open Command Prompt as Administrator.
   - Type chkdsk /f and follow prompts.

3. **Manually Reset Windows Update Components**
- Open Command Prompt as Administrator Search for "cmd" in the Start menu. Right-click on Command Prompt and select Run as administrator
- Delete the SoftwareDistribution and Catroot2 Folders
- Restart the Stopped Services
- Check for Windows Updates After resetting the components, close the Command Prompt and go to Settings > Update & Security > Windows Update.
  Click on Check for updates to see if the update process works correctly.

**URL**
(https://www.minitool.com/partition-disk/win10-wont-update.html)

(https://www.easeus.com/computer-instruction/windows-update-not-working.html?srsltid=AfmBOopRzh4uEtoib7pK8rlE4tl943xJaeFiE6xZ9E07GslqeBz8iOAq)

   
