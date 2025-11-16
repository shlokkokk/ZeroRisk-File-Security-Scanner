# ZeroRisk Sentinel 🔒
> **Advanced Cybersecurity File Analysis Tool with Hacker-Themed Interface**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-ZeroRisk%20Sentinel-blue?style=for-the-badge)](https://shlokkokk.github.io/ZeroRisk-File-Security-Scanner/)
 https://shlokkokk.github.io/ZeroRisk-File-Security-Scanner

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Overview

ZeroRisk Sentinel is a cutting-edge cybersecurity tool designed to analyze files for malware, extension spoofing, and security threats. Built with a professional hacker-themed interface, it provides comprehensive file security analysis using advanced detection techniques.

### ✨ Key Features

- **🔍 File Header Analysis** - Detects extension spoofing and file type mismatches
- **🦠 Malware Detection** - Detects unsafe patterns, malicious strings, and suspicious API usage
- **⌨️ Keylogger Detection** - Identifies keystroke logging functionality
- **📊 Real-time Analysis** - Live scanning with animated progress indicators
- **🎨 Hacker-Themed UI** - Professional cybersecurity interface with matrix effects
- **📱 Responsive Design** - Works on desktop and mobile devices
- **🔒 Privacy-First** - All analysis happens client-side, no data upload

## 📁 Project Structure

```
ZeroRisk-File-Security-Scanner/
├── index.html              # Main file scanner interface
├── results.html            # Analysis results and reports
├── about.html              # Methodology and documentation
├── main.js                 # Core JavaScript functionality
├── resources/              # Media assets
│   ├── hero-cyber.jpg      # Hero background image
│   ├── matrix-bg.jpg       # Matrix-style background
│   ├── shield-icon.png     # Security shield icon
│   └── hacker-avatar.jpg   # Cybersecurity expert avatar
└── README.md               # This file
```

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the project files
2. Open `index.html` in your web browser
3. Start analyzing files immediately!

### Option 2: Local Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/shlokkokk/ZeroRisk-File-Security-Scanner
cd ZeroRisk-File-Security-Scanner

# Start a local server
python -m http.server 8000
# or
npx serve .

# Open in browser
# Navigate to http://localhost:8000
```

## 📋 Installation Guide

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required!

### Step-by-Step Installation

1. **Download the Project**
   ```bash
   # Using git
   git clone https://github.com/shlokkokk/ZeroRisk-File-Security-Scanner
   
   # Or download ZIP from GitHub
   # Extract to your desired location
   ```

2. **Navigate to Project Directory**
   ```bash
   cd ZeroRisk-File-Security-Scanner
   ```

3. **Start Local Development Server**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the Application**
   - Open your web browser
   - Navigate to `http://localhost:8000`
   - Start using CyberGuard File Analyzer!

## 🎯 How to Use

### File Analysis Process

1. **Drop Files**
   - Drag and drop files onto the scanning zone
   - Or click to select files from your device
   - Supports multiple file selection

2. **Real-Time Analysis**
   - Watch as files are analyzed in real-time
   - View progress indicators and live updates
   - See threat levels update dynamically

3. **Review Results**
   - Check the security score and threat assessment
   - Review detailed findings for each file
   - View recommendations and actions

4. **Take Action**
   - Quarantine suspicious files
   - Export detailed reports
   - Share analysis results

### Supported File Types

The analyzer can detect and analyze over 127 file formats including:

- **Documents**: PDF, DOC, DOCX, XLS, XLSX, PPT, PPTX, RTF, TXT
- **Images**: JPEG, PNG, GIF, BMP, TIFF
- **Archives**: ZIP, RAR, 7Z, TAR, GZ
- **Executables**: EXE, DLL, MSI, APK, JAR
- **Media**: MP3, MP4, AVI, WMV, MOV, FLV
- **Code**: JS, HTML, CSS, PHP, Python, Java
- **System**: BAT, CMD, PS1, VBS, WSF

### Threat Level Thresholds

```javascript
// Threat level calculation
const threatLevels = {
    safe: 0,
    low: 10,
    medium: 25,
    high: 50,
    critical: 80
};
```

## 🔒 Security Features

### Client-Side Analysis
- All file analysis happens in your browser
- No data is uploaded to external servers
- Protects your privacy and sensitive files

### Threat Detection
- **Signature-Based Detection**: Heuristic pattern detection
- **Heuristic Analysis**: Suspicious behavior patterns
- **Extension Spoofing Detection**: File type mismatch identification
- **Keylogger Detection**: Keystroke logging functionality detection

### Real-Time Protection
- Live scanning with animated progress
- Immediate threat assessment
- Dynamic threat level updates
- Interactive security dashboards

## 📊 Analysis Capabilities

### File Header Analysis
```javascript
// Detect file type from header bytes
const fileType = detectFileType(headerBytes);
if (fileType !== fileExtension) {
    flagExtensionSpoofing(file.name, fileType, fileExtension);
}
```

### Malware Signature Scanning
```javascript
// Scan file content for malware patterns
const malwareFindings = scanForMalware(fileContent);
if (malwareFindings.length > 0) {
    updateThreatLevel(file.name, 'critical');
}
```

### Keylogger Detection
```javascript
// Check for keylogger behavior patterns
const keyloggerDetected = detectKeylogger(fileContent, file.name);
if (keyloggerDetected) {
    flagKeylogger(file.name);
}
```

## 🌐 Deployment Options

### Traditional Web Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Access via your domain name

## 🐛 Troubleshooting

### Common Issues

**Files not scanning?**
- Check browser console for errors
- Ensure JavaScript is enabled
- Try refreshing the page

**Animations not working?**
- Verify all JavaScript libraries are loaded
- Check for JavaScript errors in console
- Ensure CSS files are properly linked

**Mobile display issues?**
- Clear browser cache
- Try different mobile browser
- Check responsive design breakpoints

### Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | ✅ Full Support |
| Firefox | 75+ | ✅ Full Support |
| Safari | 13+ | ✅ Full Support |
| Edge | 80+ | ✅ Full Support |
| Opera | 67+ | ✅ Full Support |

### Contribution Areas
- 🐛 Bug fixes
- ✨ New features
- 📚 Documentation improvements
- 🎨 UI/UX enhancements
- 🔒 Security improvements
- 📈 Performance optimizations

<div align="center">
    <p><strong>ZeroRisk Sentinel</strong> - Protecting your digital world, one file at a time.</p>
    <p>⭐ Star this repository if you find it useful!</p>
</div>
