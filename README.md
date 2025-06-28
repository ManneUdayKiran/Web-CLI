
# 🖥️ Web CLI Terminal

A fully browser-based command-line interface that mimics real CLI behavior using a simulated in-memory file system. No backend or actual file system access required. Built with vanilla HTML, CSS, and JavaScript.

---

## screenshots
![Uploading image.png…]()


## 🚀 Features

- Simulated file system with full in-browser state management
- Recognized commands:
  - `mkdir` – create directories
  - `ls` – list contents
  - `cd` – change current directory
  - `rmdir` – remove empty directories
  - `rm` – delete files
  - `touch` – create files
  - `mv` – move/rename files or directories
  - `cp` – copy files or directories
  - `curl` – simulate fetching data from a URL
- Rejects any other command with: `Command not recognized`
- CLI-style UI with prompt, input, and output display

---

## 🧪 Example Commands

```bash
mkdir docs
cd docs
touch readme.md
ls
cd ..
mv docs/readme.md docs/guide.md
cp docs/guide.md docs/copy.md
rm docs/copy.md
curl https://example.com/api
rmdir docs  # fails if not empty
cd docs
rm guide.md
cd ..
rmdir docs
````

---

## 📦 Tech Stack

* HTML
* CSS
* JavaScript (ES6)
* No external libraries or frameworks used

---

## 📁 Folder Structure

```
project-root/
├── index.html      # Main app
└── README.md       # Project documentation
```

---

## 📝 License

This project is open source and available under the MIT License.

```

