# Automatic File Sorter using Python

A simple Python automation project that organizes files into separate folders based on their file extensions using the `os` and `shutil` modules.

## 📌 Project Overview

Managing files manually can become time-consuming when a folder contains different types of files.

This project automates file organization by identifying file extensions and moving files into their respective folders.

The script automatically creates the required folders if they do not already exist and organizes CSV, PNG, and XLSX files.

## 🎯 Project Objectives

- Automate file organization.
- Identify files based on their extensions.
- Create folders automatically.
- Move files into their respective folders.
- Reduce manual file management.

## 🛠️ Technologies Used

- **Python** – Core programming language.
- **OS Module** – To list files, check directories, and create folders.
- **Shutil Module** – To move files between directories.
- **Jupyter Notebook** – Development environment.

## ⚙️ How It Works

1. Specify the folder path containing the files.
2. Retrieve the list of files using `os.listdir()`.
3. Create separate folders for CSV, image, and Excel files.
4. Identify files based on their extensions.
5. Move the files into their corresponding folders using `shutil.move()`.

## 📂 Folder Organization

The project organizes files into the following structure:

```text
sorter demo/
│
├── csv files/
│   └── *.csv
│
├── Image files/
│   └── *.png
│
└── excel files/
    └── *.xlsx
```

## 🚀 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Starlin7/Automatic-File-Sorter-Python.git
```

Navigate to the project directory:

```bash
cd Automatic-File-Sorter-Python
```

### 2. Install Python

Make sure Python is installed on your computer.

No additional third-party libraries are required because the project uses Python's built-in `os` and `shutil` modules.

### 3. Configure the Folder Path

Open the Jupyter Notebook and update the folder path:

```python
path = r"C:/Users/YourName/Documents/sorter demo/"
```

Replace the example path with the directory containing the files you want to organize.

**Important:** Make sure the path points to the correct folder.

### 4. Run the Notebook

Execute the notebook cells in order.

The script will automatically create the required folders and move the supported files into them.

## 📁 Supported File Types

| File Extension | Destination Folder |
|---|---|
| `.csv` | csv files |
| `.png` | Image files |
| `.xlsx` | excel files |

## 📚 Key Concepts Learned

- File and directory handling using Python.
- Working with the `os` module.
- Moving files using the `shutil` module.
- Checking file extensions.
- Creating directories programmatically.
- Automating repetitive tasks.

## 🔮 Future Enhancements

- Support additional file formats such as PDF, DOCX, JPG, and TXT.
- Automatically organize files in multiple directories.
- Add a graphical user interface.

## 👨‍💻 Author

**Starlin Pereira**

