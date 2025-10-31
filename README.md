# Recoil Control

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![AI Assisted](https://img.shields.io/badge/AI%20Enhanced-GitHub%20Copilot-brightgreen.svg)
![Human Intelligence](https://img.shields.io/badge/Human%20Crafted-p4rsao-orange.svg)

A sophisticated gaming enhancement tool created through the synergy of artificial and human intelligence. This innovative application combines the precision of AI-assisted development (GitHub Copilot) with human expertise in gaming mechanics to deliver a powerful recoil control solution.

## 🤝 Development Approach

This project represents a unique collaboration between:

- 🧠 **Human Intelligence** (@p4rsao):
  - Core concept and gaming expertise
  - User experience design
  - Performance optimization
  - Real-world gaming scenario testing

- 🤖 **Artificial Intelligence** (GitHub Copilot):
  - Code structure optimization
  - Best practices implementation
  - Error handling patterns
  - Documentation assistance

The result is a robust, efficient, and user-friendly tool that leverages the best of both worlds - human gaming intuition and AI-powered development practices.

![Mouse Controller Screenshot](assets/screenshot.png)

## 🎯 Features

- 🖱️ Automatic downward mouse movement
- ⚡ Adjustable movement speed (1-20 pixels)
- 🎮 Gaming-optimized controls
- ⌨️ Convenient hotkeys (F7/F8)
- 🎨 Clean and intuitive GUI
- 🔝 Always-on-top window

## 🚀 Quick Start

### Prerequisites

- Python 3.6 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/parsasdg8/Recoil-Control.git
cd Recoil-Control
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

### Running the Application

```bash
python src/recoil_control.py
```

## 📖 How to Use

1. Launch the application
2. Press `F7` or click "Enable" button to activate
3. Hold left mouse button to trigger automatic downward movement
4. Use the slider to adjust movement speed
5. Press `F8` or click "Disable" button to deactivate

## 🛠️ Building Executable

To create a standalone executable:

```bash
pyinstaller --noconfirm --onefile --windowed --icon="assets/icons8-ak-47-67.ico" --add-data "assets/icons8-ak-47-67.ico;." --name="Recoil Control" src/recoil_control.py
```

The executable will be created in the `dist` folder.

## 🎮 Use Cases

- Gaming automation
- Scrolling through long documents
- Automated testing
- Any task requiring consistent downward mouse movement

## 🔧 Technical Details

### Built with:
- Python 3.x
- Tkinter (GUI)
- PyAutoGUI (Mouse control)
- Pynput (Keyboard/Mouse monitoring)

### Development Stack:
- 💻 VS Code with GitHub Copilot
- 🧪 Test-driven development
- 🎮 Real-world gaming scenarios
- 📊 Performance optimization

### AI Integration:
- Code structure and patterns suggested by GitHub Copilot
- Enhanced error handling through AI assistance
- Documentation generation with AI support
- Best practices implementation guided by AI

### Human Touch:
- Gaming expertise from real-world experience
- User interface designed for gamers
- Performance tuning based on actual usage
- Customization options for different gaming styles

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

- [@parsasdg8](https://github.com/parsasdg8)

## ⭐ Show your support

Give a ⭐️ if this project helped you!