# WatermarkPro - Universal Watermarking Tool

A powerful, privacy-focused web application for adding watermarks to PDFs and images. Built with React and vanilla JavaScript, all processing happens locally in your browser - no files are uploaded to any server.

!https://aryan-git-byte.github.io/Watermark-adder/

## ✨ Features

### 🔐 Privacy First
- **100% Client-Side Processing** - Files never leave your browser
- **No Server Upload** - Everything runs locally
- **Instant Processing** - No waiting for uploads/downloads

### 📄 File Support
- **PDF Files** - Watermark any PDF document
- **Images** - Support for JPG, JPEG, PNG formats
- **Batch Processing** - Handle multiple files at once
- **ZIP Download** - Automatically packages multiple processed files

### 🎨 Watermark Types
- **Text Watermarks**
  - 100+ Google Fonts with live search
  - Full typography control (bold, italic, letter spacing)
  - Custom colors and opacity
  - Size and rotation controls

- **Image/Logo Watermarks**
  - Upload PNG, JPG, JPEG, SVG files
  - Automatic scaling and positioning
  - Transparency support

### 🎯 Positioning Options
- **Auto Positioning** - 9 preset positions plus diagonal
- **Manual Control** - Drag, resize, and rotate watermarks visually
- **Tiled Patterns** - Repeat watermarks across the entire document
- **Layer Modes** - Above or blended overlay options

### 🌙 Modern UI
- **Dark/Light Mode** - Automatic system theme detection
- **Glassmorphism Design** - Modern blur effects and transparency
- **Responsive Layout** - Works on desktop and mobile
- **Live Preview** - See changes in real-time

## 🚀 Demo

Try it live: [WatermarkPro Demo](https://aryan-git-byte.github.io/watermark-pro)

## 🛠️ Technologies

- **Frontend**: React 18, Tailwind CSS
- **PDF Processing**: PDF-lib, PDF.js
- **Image Processing**: HTML5 Canvas
- **File Handling**: JSZip for batch downloads
- **Fonts**: Google Fonts API integration

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/aryan-git-byte/watermark-pro.git
cd watermark-pro
```

2. Open `index.html` in your browser or serve with any static server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Or simply open index.html in your browser
```

## 🎮 Usage

1. **Upload Files**: Click "Choose Files" and select PDFs or images
2. **Choose Watermark Type**: Select text or image watermark
3. **Customize**: Adjust font, size, color, position, and opacity
4. **Position**: Use auto-positioning or manual drag-and-drop control
5. **Preview**: See live preview of your watermarked files
6. **Download**: Get individual files or ZIP archive for multiple files

### Manual Control Mode
- **Drag**: Click and drag watermark to reposition
- **Resize**: Use corner handles to resize
- **Rotate**: Use the green handle above the watermark
- **Visual Feedback**: Real-time preview updates

## 🔧 Configuration

The app works out of the box with no configuration needed. All dependencies are loaded via CDN:

- React 18
- PDF-lib 1.17.1
- PDF.js 3.11.174
- JSZip 3.10.1
- Google Fonts API

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google Fonts for the extensive font library
- PDF-lib for excellent PDF manipulation capabilities
- React team for the amazing framework
- Tailwind CSS for the utility-first styling approach



## 🔮 Roadmap

- [ ] Video watermarking support
- [ ] Advanced text effects (shadows, outlines)
- [ ] Watermark templates and presets
- [ ] Batch operation scheduling
- [ ] Extended file format support
- [ ] API integration options

---

⭐ If you find this project helpful, please consider giving it a star on GitHub!
