
# Win11

https://schneegans.de/windows/unattend-generator/



1. Go to [Microsoft Store](https://apps.microsoft.com/store/apps).
2. Search for your desired app.
3. Copy the ID from the URL. For example: `9WZDNCRFJ3TJ`.
4. Run the following command to install the app:

   ```bash
   winget install 9WZDNCRFJ3TJ -s msstore


##Install Chocolatey

  ```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
