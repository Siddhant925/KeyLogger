# KeyLogger – Python Based Keystroke Logger

## 📌 Project Overview

KeyLogger is a simple Python-based application that records keyboard activities using the `pynput` library. It provides a graphical user interface (GUI) built with Tkinter, allowing users to start the keystroke logging process.

The application records key press, key hold, and key release events and stores the collected information in both JSON and text file formats.

**Note:** This project is developed for educational purposes to understand keyboard event handling, Python programming, and file handling. Use it only on your own device or with the explicit consent of the device user.

## ✨ Features

- **Graphical User Interface:** Simple GUI developed using Tkinter.
- **Keyboard Event Monitoring:** Detects key press and release events.
- **Key Event Tracking:** Records pressed, held, and released key events.
- **JSON Logging:** Stores keyboard event information in a structured JSON format.
- **Text File Logging:** Saves recorded keystrokes in a text file.
- **Python-Based:** Developed using Python and its libraries.

## 🛠️ Technologies Used

- Python 3
- Tkinter – Graphical User Interface
- Pynput – Keyboard event monitoring
- JSON – Structured data storage

## 📂 Project Structure

```text
KeyLogger/
│
├── main.py          # Main Python application
├── logs.txt         # Recorded keystrokes
├── logs.json        # Keyboard event records
└── README.md        # Project documentation
```

## ⚙️ Installation and Setup

### 1. Install Python

Download and install Python 3 from:

https://www.python.org/downloads/

### 2. Install Required Library

Open your terminal or command prompt and execute:

```bash
pip install pynput
```

**Note:** Tkinter is generally included with standard Python installations.

### 3. Clone the Repository

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd KeyLogger
```

### 4. Run the Application

Execute the following command:

```bash
python main.py
```

## 🚀 Working

1. Run the Python application.
2. A graphical window appears with a warning message.
3. Click the **Start KeyLogger** button.
4. The application begins listening for keyboard events.
5. Keyboard event information is written to `logs.json` and `logs.txt`.

## 📄 Output Files

| File | Description |
|---|---|
| `logs.txt` | Stores the collected keystroke text. |
| `logs.json` | Stores keyboard events in JSON format, including press, hold, and release events. |

### Sample JSON Output

```json
[
    {
        "Pressed": "'a'"
    },
    {
        "Held": "'a'"
    },
    {
        "Released": "'a'"
    }
]
```

## 🔒 Privacy and Security

- Use this application only for authorized educational testing.
- Do not record another person's keyboard activity without their informed consent.
- Do not use this application to collect passwords, banking information, or other sensitive data.
- Keep generated log files private and delete them after testing.

## ⚠️ Limitations

- The application currently provides basic keyboard event tracking.
- The listener runs continuously until stopped externally.
- The current implementation may make the Tkinter interface unresponsive after starting the listener.
- Keyboard monitoring permissions may vary depending on the operating system.

## 🎯 Learning Outcomes

Through this project, the following concepts can be understood:

- Python event-driven programming.
- Keyboard event handling using Pynput.
- GUI development using Tkinter.
- File handling in Python.
- JSON serialization and data storage.

## 👨‍💻 Author

**Developed as a Python programming and cybersecurity learning project.**

