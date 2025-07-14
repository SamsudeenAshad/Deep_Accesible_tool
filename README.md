# Deep Accessibility Tool Browser Extension

A comprehensive browser extension designed to enhance web accessibility for users with diverse needs.

## 🌟 Features

### 📝 Text Adjustments
- **Increase Text Size**: Make text larger for better readability
- **Decrease Text Size**: Reduce text size when needed

### 🎨 Visual Enhancements
- **Grayscale Mode**: Convert pages to grayscale for better focus
- **High Contrast**: Enhance contrast for better visibility
- **Negative Contrast**: Invert colors for reduced eye strain
- **Light Background**: Force light backgrounds for better readability
- **Dark Mode**: Apply dark theme for reduced eye strain and better night viewing

### 🔗 Link Enhancements
- **Links Underline**: Make all links clearly underlined

### 📖 Typography
- **Readable Font**: Apply clean, readable fonts across pages

### 🔄 Reset Function
- **Reset All**: Quickly return to default settings

## 🚀 Installation

### For Development:
1. Clone this repository
2. Open Chrome/Edge and go to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension folder
5. The extension will appear in your browser toolbar

### For Production:
1. Package the extension as a .crx file
2. Upload to Chrome Web Store or Edge Add-ons store

## 💻 How to Use

1. Click the extension icon in your browser toolbar
2. Select the accessibility features you need
3. Settings are automatically saved and applied
4. Use "Reset All" to return to defaults

## 🛠️ Technical Details

### Files Structure:
- `manifest.json` - Extension configuration
- `popup.html` - Extension popup interface
- `popup.css` - Popup styling
- `popup.js` - Popup functionality
- `content.js` - Main accessibility features
- `background.js` - Background service worker
- `accessibility.css` - Additional accessibility styles

### Permissions Required:
- `activeTab` - Access current tab content
- `storage` - Save user preferences
- `scripting` - Inject accessibility scripts

## 🔧 Browser Compatibility

- ✅ Chrome (Manifest V3)
- ✅ Microsoft Edge
- ✅ Opera
- ✅ Brave
- ⚠️ Firefox (requires Manifest V2 adaptation)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

If you encounter any issues or have suggestions:
1. Check existing issues on GitHub
2. Create a new issue with detailed description
3. Include browser version and steps to reproduce

## 🔮 Future Features

- Voice control integration
- Custom color schemes
- Reading mode
- Text-to-speech
- Keyboard navigation enhancements
- Screen reader optimizations

## 📊 Privacy

This extension:
- ✅ Works locally on your device
- ✅ Doesn't collect personal data
- ✅ Doesn't send data to external servers
- ✅ Settings stored locally in your browser

---

Made with ❤️ for accessibility and inclusion