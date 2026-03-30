# Star Pusher ⭐

![GitHub release (latest by date)](https://img.shields.io/github/v/release/ShivamKR12/starpusher)
![CI](https://github.com/ShivamKR12/starpusher/actions/workflows/build.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.x-blue)
![Pygame](https://img.shields.io/badge/pygame-ce-green)

**Star Pusher** is a classic **Sokoban-style puzzle game** built with **Python and Pygame Community Edition**.
Your goal is to push stars onto their designated goal tiles while navigating through increasingly challenging levels.

---

# 🎮 Game Description

In **Star Pusher**, you control a character exploring a tile-based puzzle map. Each level contains:

* ⭐ **Stars** that must be pushed
* 🎯 **Goal tiles** where the stars must end up
* 🧱 **Walls and obstacles**
* 🌳 **Decorations** such as trees and rocks

Your objective is simple:

> **Push every star onto a goal tile to solve the level.**

But be careful — stars can only be pushed **one at a time**, and pushing them into corners may make the puzzle impossible to solve!

---

# ✨ Features

* 🧩 **Sokoban-style puzzle gameplay**
* 🗺️ **Multiple handcrafted levels**
* 🎭 **Selectable player characters**
* 🎥 **Movable camera for exploring large maps**
* 🌳 **Procedurally decorated environments**
* 🔄 **Level reset and navigation**
* 💻 **Cross-platform support** (Windows, macOS, Linux)
* ⚡ **Lightweight Python + Pygame implementation**

---

# 🕹️ Controls

| Key           | Action                  |
| ------------- | ----------------------- |
| ⬆️⬇️⬅️➡️      | Move player             |
| **W A S D**   | Move camera             |
| **P**         | Change player character |
| **Backspace** | Reset current level     |
| **N**         | Next level              |
| **B**         | Previous level          |
| **ESC**       | Quit game               |

---

# 🚀 Installation and Running

## Option 1 — Download Executable (Recommended)

1. Go to the **Releases page**
   https://github.com/ShivamKR12/starpusher/releases

2. Download:

```
starpusher.zip
```

3. Extract the archive.

4. Run:

```
starpusher.exe
```

No Python installation required.

---

# 🧑‍💻 Running from Source

## Requirements

* Python **3.7+**
* **pygame-ce**

Install dependency:

```bash
pip install pygame-ce
```

Run the game:

```bash
python starpusher.py
```

---

# 🛠️ Building the Executable

You can build the game yourself using **PyInstaller**.

Install PyInstaller:

```bash
pip install pyinstaller
```

Build the executable:

```bash
pyinstaller starpusher.spec
```

After building, the executable will appear in:

```
dist/
```

---

# 📁 Project Structure

```
starpusher
│
├── starpusher.py
├── starPusherLevels.txt
├── Star.png
├── princess.png
├── boy.png
├── catgirl.png
├── horngirl.png
├── pinkgirl.png
├── Grass_Block.png
├── Plain_Block.png
├── Wall_Block_Tall.png
├── Wood_Block_Tall.png
├── Rock.png
├── Tree_Short.png
├── Tree_Tall.png
└── Tree_Ugly.png
```

---

# 📸 Screenshots

*(Add gameplay screenshots here)*

Example:

* Title Screen
* Puzzle Gameplay
* Solved Level Screen

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```
git checkout -b feature/my-feature
```

3. Commit your changes

```
git commit -m "Add new feature"
```

4. Push to GitHub

```
git push origin feature/my-feature
```

5. Open a Pull Request 🚀

---

# 📄 License

This project is licensed under the **MIT License**.

See the LICENSE file for details.

---

# 🙏 Credits

Developer: **ShivamKR12**

Built with:

* Python
* Pygame Community Edition

Inspired by the classic puzzle genre **Sokoban**.

---

# 📬 Support

If you encounter issues:

* Open a GitHub issue
  https://github.com/ShivamKR12/starpusher/issues

* Check the CI build status
  https://github.com/ShivamKR12/starpusher/actions

---

⭐ If you enjoy the project, consider giving it a **star on GitHub!**
