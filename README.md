# update_app
# Update Server Instructions

## Steps to Add a New Version

1. Create a new folder with your version number (e.g. `0.2.0/`)

2. Copy the following files to the version folder:
   - Installer file (e.g. `emis_tauri_0.2.0_x64-setup.exe`) 
   - Signature file (e.g. `emis_tauri_0.2.0_x64-setup.exe.sig`)

3. Update `latest.json` with:
   - New version number
   - Signature content (as string from .sig file)
   - URL path to the installer

Example `latest.json`:
