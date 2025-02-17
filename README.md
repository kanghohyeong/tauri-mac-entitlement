This project is a default Tauri project created using `npm create tauri-app@latest`. 

The only modifications are
- tauri.conf.json
    - Added entitlements and signingIdentity under the bundle > macOS section
- Entitlements.plist
    - Set app-sandbox to true
- Environment Variable Configuration
    - Exported the APPLE_SIGNING_IDENTITY environment variable