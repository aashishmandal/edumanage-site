# 📦 EduManage Update Manifest

This repository hosts the update manifest (`version.json`) for the 
[EduManage](https://github.com/aashishmandal/EduManage) desktop application.
The file is served via GitHub Pages and used by EduManage to check for new versions 
and download updates automatically.

---

## 🔄 Auto-Update System

EduManage reads the following file on launch:

📄 [version.json](https://aashishmandal.github.io/edumanage-site/version.json)

### Example structure:
`
```json
{
  "latest_version": "1.1.0",
  "download_url": "https://github.com/aashishmandal/EduManage/releases/download/v1.1.0/EduManageSetup.exe"
}
```
## 🛠️ How to Update

Edit docs/version.json
Change "latest_version" to your new release tag
Update "download_url" to point to the new installer
Commit the change — GitHub Pages will serve it instantly

##🔐 Note

This repo does not contain application code. To view or download EduManage, visit the main repo:
👉 https://github.com/aashishmandal/EduManage

## 👤 Maintainer
Aashish Mandal 📧 aashishmandalofficial@gmail.com

