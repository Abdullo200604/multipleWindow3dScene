# Multiple Window 3D Scene using Three.js

## 📌 Introduction
This project demonstrates an advanced technique for rendering and synchronizing a 3D scene across multiple browser windows using [Three.js](https://threejs.org) and the browser's `localStorage`. It's aimed at developers exploring interactive multi-window 3D applications.

## ✨ Features
- 🌐 Real-time 3D scene rendering with Three.js
- 🪟 Multi-window scene synchronization
- 📦 Dynamic window state management using `localStorage`
- 🧠 Modular architecture (`main.js` + `WindowManager.js`)

## 🚀 Getting Started

### ✅ Clone the repository

```bash
git clone https://github.com/Abdullo200604/multipleWindow3dScene.git
▶️ Run the project
Simply open index.html in your browser — no build tools or servers required.

Or, for a quick local server:

bash
Копировать
Редактировать
# Python 3
python -m http.server 8000
# Then open http://localhost:8000 in your browser
📁 Project Structure
File / Folder	Description
index.html	Main HTML file. Loads the 3D scene and scripts.
main.js	Initializes and renders the Three.js scene, manages events.
WindowManager.js	Handles multi-window management and synchronization via localStorage.
three.r124.min.js	Minified Three.js library used for rendering.

⚙️ How It Works
Each opened window creates a new instance with metadata (ID, size, position).

WindowManager.js synchronizes window data across all open tabs using localStorage.

main.js renders the 3D scene (customizable) for each window and updates it on resize or movement.

🧱 Technologies Used
Three.js — for 3D rendering

Native JavaScript (ES6+ modules)

Browser APIs: localStorage, window.resize, beforeunload

🤝 Contributing
Contributions are welcome!
Fork the repository, create a new branch, make your changes, and submit a pull request. Suggestions for new features, improvements, or bug fixes are appreciated.

📜 License
This project is open-source and licensed under the MIT License.

🙏 Acknowledgments
Three.js — for the powerful and easy-to-use 3D engine

Original idea inspired by bgstaal/multipleWindow3dScene

Special thanks to the open-source community

👤 Author
Maintained by @Abdullo200604
