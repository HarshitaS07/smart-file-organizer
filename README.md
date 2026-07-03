# 📂 Smart File Organizer

> A Python application that automatically organizes files into categorized folders based on their file extensions.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/Status-Under%20Development-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

---

# 📖 Overview
Managing a cluttered Downloads folder is a common problem. Images, documents, videos, PDFs, compressed files, and many other file types quickly accumulate, making it difficult to find important files.

**Smart File Organizer** automatically scans a directory, identifies each file based on its extension, creates category folders if they do not already exist, and organizes files into their appropriate locations.

This project is part of my Software Engineering Portfolio and is being developed to strengthen my understanding of Python, software engineering principles, clean architecture, file systems, and professional development practices.

---

# 🎯 Problem Statement

Modern computers accumulate hundreds of downloaded files over time.

Most users either:

- manually organize files (which is time-consuming), or
- never organize them at all.

The objective of this project is to automate this process while providing a clean, extensible, and maintainable solution.

---

# 💡 Solution

The application will:

- Scan a target directory
- Identify every file based on its extension
- Categorize files automatically
- Create folders dynamically if required
- Move files into their appropriate locations
- Generate logs for every operation
- Be designed for future scalability

---

# ✨ Features

## ✅ Current

- Project initialization
- Software architecture planning
- Git version control
- Documentation

## 🚧 Under Development

- Scan folders
- Detect file extensions
- Automatic folder creation
- File organization
- Logging
- Exception handling

## 🔮 Planned

- Duplicate file detection
- Undo previous organization
- Custom organization rules
- Organize by creation date
- Organize by file size
- Automatic scheduled organization
- Desktop GUI
- AI-powered file categorization
- Cloud storage support

---

# 🏗 System Architecture

```
                User
                  │
                  ▼
        Select Target Folder
                  │
                  ▼
          Scan Directory
                  │
                  ▼
      Detect File Extensions
                  │
                  ▼
      Determine File Category
                  │
                  ▼
     Create Folder (if needed)
                  │
                  ▼
           Move File
                  │
                  ▼
           Generate Logs
                  │
                  ▼
             Completed
```

---

# ⚙ Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python 3 |
| Libraries | pathlib, shutil, os, logging |
| Version Control | Git |
| Repository Hosting | GitHub |
| IDE | VS Code |

---

# 📂 Project Structure

```
smart-file-organizer/

│
├── main.py
├── organizer.py
├── config.py
├── logger.py
├── README.md
├── requirements.txt
│
├── test_folder/
│
├── logs/
│
└── screenshots/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/smart-file-organizer.git
```

Navigate to the project directory

```bash
cd smart-file-organizer
```

Run the application

```bash
python main.py
```

---

# 🛠 Usage

1. Choose the folder to organize.
2. Run the program.
3. The application scans all files.
4. Files are categorized automatically.
5. New folders are created if required.
6. Files are moved into their respective folders.

---

# 🧠 Engineering Concepts Practiced

This project is intentionally designed to reinforce core software engineering concepts.

- Python programming
- File handling
- Directory traversal
- Object-Oriented Design (future versions)
- Modular programming
- Exception handling
- Logging
- Software architecture
- Git workflow
- Documentation

---

# ⚡ Challenges

Some engineering challenges expected during development include:

- Handling duplicate filenames
- Managing unsupported file extensions
- Preventing accidental overwriting
- Cross-platform file path compatibility
- Permission-related errors
- Designing scalable categorization rules

---

# 🧪 Testing Strategy

The application will be tested using:

- Manual testing
- Edge case testing
- Mixed file types
- Empty folders
- Nested directories
- Duplicate filenames

---

# 📈 Development Timeline

| Version | Description |
|----------|-------------|
| v0.1 | Project Planning & Repository Setup |
| v0.2 | Folder Scanning |
| v0.3 | Extension Detection |
| v0.4 | File Categorization |
| v0.5 | File Moving |
| v0.6 | Logging |
| v0.7 | Error Handling |
| v1.0 | Stable Release |

---

# 🛣 Development Roadmap

- [x] Define project scope
- [x] Create GitHub repository
- [x] Write documentation
- [ ] Implement folder scanning
- [ ] Detect file extensions
- [ ] Create folders automatically
- [ ] Move files
- [ ] Logging
- [ ] Exception handling
- [ ] Testing
- [ ] Documentation updates
- [ ] Version 1.0 Release

---

# 📚 Learning Journal

This section will be continuously updated throughout development.

### Lessons learned

- Project planning before implementation
- Professional GitHub repository organization

---

# 🔮 Future Enhancements

- Desktop application using Tkinter
- Drag-and-drop interface
- File preview
- ZIP archive organization
- Cloud synchronization
- AI-powered categorization
- Duplicate detection using hashing
- Automatic scheduled execution
- Configuration through JSON/YAML

---

# 📸 Screenshots

Screenshots will be added as the project progresses.

---

# 🤝 Contributing

Contributions, suggestions, and feedback are always welcome.

If you would like to contribute:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

**Harshita**

Integrated M.Tech Computer Science and Engineering

Currently building practical software projects while exploring:

- Python
- Software Engineering
- Artificial Intelligence
- Data Science
- Backend Development

---

⭐ If you found this project interesting, consider giving it a star!
