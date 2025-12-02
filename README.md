<img src="docs/logo_macmilling.png" style="height:64px;margin-right:32px"/>

# FFmpeg Web-UI

<div align="center">


**A powerful web-based graphical user interface for FFmpeg functionalities**

[
[
[
[
[

[Features](#features) -  [Getting Started](#getting-started) -  [Usage](#usage) -  [Modules](#modules) -  [Contributing](#contributing)

</div>

***

## 📖 About

**FFmpeg Web-UI** is a modern, browser-based graphical user interface designed to facilitate the utilization of FFmpeg functionalities without requiring command-line knowledge. Built with vanilla JavaScript and featuring a responsive design, this application provides an intuitive and user-friendly interface for video processing tasks.

Developed by **MacMilling Computer Software Entertainment Technologies Lit.**, this project aims to democratize access to powerful video manipulation tools through an accessible web interface.

## ✨ Features

- 🎨 **Modern UI/UX**: Clean, professional interface with dark mode support
- 📱 **Responsive Design**: Seamless experience across desktop and mobile devices
- 🎬 **Frame Extraction**: Advanced video frame extraction with multiple preset modes
- 🌳 **Modular Architecture**: Tree-view navigation structure ready for expansion
- ⚡ **Client-Side Processing**: All video processing happens in the browser using HTML5 Canvas API
- 🎯 **Multiple Output Formats**: Support for PNG, JPEG, WebP, and BMP formats
- 📊 **Real-Time Progress Tracking**: Live updates during processing operations
- 🔒 **Privacy-Focused**: No server uploads – your files stay in your browser


## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required


### Installation

1. **Clone the repository**

```bash
git clone https://github.com/MacMillingComputerSoftwareEntertainment/ffmpeg-web-ui.git
```

2. **Navigate to the project directory**

```bash
cd ffmpeg-web-ui
```

3. **Open the application**

Simply open `index.html` in your web browser, or serve it using a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

4. **Access the application**

Navigate to `http://localhost:8000` in your browser

## 💻 Usage

### Frames Extract Module

The **Frames Extract** module allows you to extract frames from video files with precision and flexibility.

#### Basic Workflow

1. **Add Video Files**
    - Click "Add Video Files" button
    - Select one or multiple video files from your device
    - Supported formats: MP4, WebM, OGG, AVI, MOV (browser-dependent)
2. **Configure Extraction Settings**

Choose from preset modes:
    - **Extract All Frames**: Captures every single frame
    - **1 Frame/Second**: One frame per second
    - **Every 30 Seconds**: Time-based interval extraction
    - **Every 1 Minute**: 60-second interval extraction
    - **25 Frames Total**: Evenly distributed throughout the video
    - **Custom Settings**: Define your own extraction parameters
3. **Customize Output**
    - Select output format (PNG, JPEG, WebP, BMP)
    - Adjust quality settings for compressed formats
    - Configure destination folder and naming patterns
    - Enable/disable subfolder creation per video
4. **Start Extraction**
    - Click "Start Extraction"
    - Monitor real-time progress
    - Frames automatically download to your browser's download folder

#### Custom Settings

For advanced users, the Custom Settings mode offers:

- **Interval (Seconds)**: Extract frames at specific time intervals
- **Frame Count**: Extract every Nth frame
- **Total Frames**: Specify exact number of frames to extract (evenly distributed)


#### Output Options

- **Format**: PNG (lossless), JPEG (compressed), WebP (modern), BMP (uncompressed)
- **Quality**: Adjustable quality for JPEG/WebP (1-31 scale)
- **Naming Patterns**:
    - `frame_0001, frame_0002...`
    - `videoname_frame_0001...`
    - `videoname_0001, videoname_0002...`
    - `timestamp_0001...`


## 🧩 Modules

### Current Modules

- ✅ **Frames Extract** - Extract video frames with customizable intervals


### Upcoming Modules

- 🔜 **Video Trimmer** - Cut and trim video segments
- 🔜 **Format Converter** - Convert between video formats
- 🔜 **Audio Extractor** - Extract audio tracks from videos
- 🔜 **Video Analyzer** - Analyze video properties and metadata


## 🏗️ Architecture

```
ffmpeg-web-ui/
├── index.html          # Main application file
├── README.md           # Project documentation
├── LICENSE             # License information
└── assets/             # Additional resources (if any)
```


### Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Video Processing**: HTML5 Canvas API
- **Design Pattern**: Component-based architecture
- **Styling**: CSS Custom Properties with dark mode support


## 🎨 Design Philosophy

The interface follows modern web design principles:

- **Consistency**: Uniform navigation and menu structure across all modules
- **Accessibility**: High contrast ratios and clear visual hierarchy
- **Responsiveness**: Fluid layouts adapting to any screen size
- **Performance**: Client-side processing eliminates network latency
- **Privacy**: No data transmission to external servers


## 🤝 Contributing

We welcome contributions from the community! Whether it's bug reports, feature requests, or code contributions, your input helps make FFmpeg Web-UI better.

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch**

```bash
git checkout -b feature/AmazingFeature
```

3. **Commit your changes**

```bash
git commit -m 'Add some AmazingFeature'
```

4. **Push to the branch**

```bash
git push origin feature/AmazingFeature
```

5. **Open a Pull Request**

### Development Guidelines

- Follow existing code style and conventions
- Test thoroughly across different browsers
- Update documentation for any new features
- Ensure backward compatibility when possible


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏢 Vendor Information

**MacMilling Computer Software Entertainment Technologies Lit.**

- Website: [Coming Soon]
- GitHub: [@MacMillingComputerSoftwareEntertainment](https://github.com/MacMillingComputerSoftwareEntertainment)


## 🙏 Acknowledgments

- FFmpeg project for providing the foundation for video processing
- The open-source community for inspiration and best practices
- All contributors who help improve this project


## 📬 Support

For questions, issues, or feature requests:

- 🐛 [Report a Bug](https://github.com/MacMillingComputerSoftwareEntertainment/ffmpeg-web-ui/issues)
- 💡 [Request a Feature](https://github.com/MacMillingComputerSoftwareEntertainment/ffmpeg-web-ui/issues)
- 📧 Contact: [Your Contact Email]


## 🗺️ Roadmap

- [x] Frame extraction functionality
- [x] Multiple preset modes
- [x] Custom extraction settings
- [x] Multiple output formats
- [ ] Video trimming module
- [ ] Format conversion module
- [ ] Audio extraction module
- [ ] Video analysis module
- [ ] Batch processing optimization
- [ ] Advanced filtering options

***

<div align="center">

**Made with ❤️ by MacMilling Computer Software Entertainment Technologies Lit.**

⭐ Star this repository if you find it helpful!

</div>
