## Description
The Manual Windows Update Tool is a PowerShell script designed to help users manually manage Windows updates. This tool provides functionality to check for available updates, install them, and track the progress of the installation process with a progress bar. The script also handles the installation of the necessary `PSWindowsUpdate` module and ensures that it is run with administrative privileges.

## Features
- **Check for Available Updates:** Identifies updates that are available for your system.
- **Install Updates with Progress Tracking:** Installs selected updates and displays a progress bar to show the installation status.
- **Automatic Module Installation:** Checks if the `PSWindowsUpdate` module is installed and prompts to install it if not.
- **Administrative Privileges Check:** Ensures that the script is run with the necessary administrative privileges.

## Installation

-   Download the `UpdateScriptWithProgress.ps1` file from the [releases page](https://github.com/DeclanE47/Manual-Windows-Update-Tool/releases) or the repository.
-   Right-click the downloaded `.ps1` file and select **"Run with PowerShell"**.

Alternative Download

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/DeclanE47/Manual-Windows-Update-Tool.git `

2.  **Navigate to the Repository Directory:**

    `cd Manual-Windows-Update-Tool`

3.  **Run the Script in PowerShell:**

    -   Make sure to run PowerShell as an Administrator.
    -   Execute the script with:

        powershell

        Copy code

        `.\UpdateScriptWithProgress.ps1`

Usage
-----

1.  The script will first check for administrative privileges and prompt for elevation if needed.
2.  It will check if the `PSWindowsUpdate` module is installed; if not, it will offer to install it.
3.  The script will then check for available Windows updates and list them.
4.  You will be prompted to install the updates. A progress bar will display the installation status.

![step1](https://github.com/user-attachments/assets/ab7969fd-4825-4f10-bfba-849f70ee32c7)

![step2](https://github.com/user-attachments/assets/2c0acbed-c9f9-4a6f-92e8-811c40588ab7)

![step3](https://github.com/user-attachments/assets/30579e26-92ba-4912-841d-4dc1f3ed7ca0)

![step4](https://github.com/user-attachments/assets/4af77194-052e-469f-8e6d-058b86387782)

License
-------

This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
------------

Contributions are welcome! Feel free to fork the repository and submit pull requests. For issues or suggestions, please open an issue on this repository.

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/emerytools)

Contact
-------

For any questions or additional information, please contact me via [GitHub](https://github.com/DeclanE47).

Acknowledgments
---------------

-   **PSWindowsUpdate Module:** This script utilizes the `PSWindowsUpdate` module, which is an essential component for managing Windows updates via PowerShell.
-   **PowerShell:** The scripting language used to create this tool, which allows for powerful system administration tasks.
