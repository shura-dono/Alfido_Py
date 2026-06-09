# Task 1: Python File Handling & Workflow Automation

This folder contains the implementation of core Python backend automation and file handling routines as part of my initial internship deliverables. The project is divided into two operational modules focusing on automated lifecycle management, structured data parsing, and robust exception frameworks.

## 📁 Files in this Task

* **`automation_task.py`**: The primary executable backend pipeline. It manages workspace environments, manipulates file states, parses structural CSV databases, and handles filesystem overheads.
* **`company_data/`**: A dynamically generated workspace sandbox containing:
    * `archived_daily_log.txt`: Automated rotation and migration target for system logs.
    * `invoices.csv`: Structured transaction tracking matrix handled via key-value mapping.

## 🛠️ Key Technical Concepts Applied

* **Automated Lifecycle Management**: Leveraging native `os` and `shutil` primitives to dynamically create directory infrastructures, route system records, and clean runtime data caches.
* **Optimized Object Matrix Iteration**: Utilizing `csv.DictReader` to parse streaming transaction entries into mapped key-value pairs, ensuring data integrity independently of explicit field ordering.
* **Enterprise Exception Handling Framework**: Implementing a highly resilient, tiered `try-except-finally` architecture explicitly designed to capture and report operational faults (`FileNotFoundError`, `PermissionError`) without risking catastrophic pipeline failure.
* **Stream Extraction & Validation**: Employing contextual file managers (`with` statements) and explicit encoding protocols (`utf-8`) to safely open, read, and write volatile system assets.

## 🚀 How to Run

1. Navigate to your project directory containing `automation_task.py`.
2. Run the automation pipeline script using Python 3:

```bash
python automation_task.py
