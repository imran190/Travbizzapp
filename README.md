# Growin CRM Android WebView App

Fixed CRM URL: `https://crm.travbizz.com/`

## What is included

- App name: **Growin**
- Fixed CRM URL opens directly on app click
- Custom premium CRM launcher icon added
- Custom splash screen removed
- File upload support
- File download support
- Phone / email / WhatsApp external link support
- GitHub Actions debug APK build workflow

## Build APK in GitHub

1. Upload/push this project to GitHub.
2. Go to **Actions**.
3. Run **Build Android APK** workflow.
4. Download artifact **growin-debug-apk**.

## Notes

- Main URL is stored in `app/src/main/res/values/strings.xml`.
- Launcher icon files are in `app/src/main/res/mipmap-*`.
- Splash dependencies and splash theme are removed so the WebView starts immediately.
