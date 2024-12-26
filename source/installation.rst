Installation
============

Follow these detailed steps to install and set up FARM-VSS on your local machine.

.. contents:: Table of Contents
   :depth: 2

Prerequisites
-------------

Before proceeding, ensure you have the following installed:

- **Python**: Version 3.7 or higher.
- **pip**: Python's package manager (usually included with Python installations).
- **Git**: For cloning the repository.
- **Visual Studio Code (VS Code)**: A code editor with support for Python extensions (optional but recommended).

Installing Required Software
----------------------------

Step 1: Install Python
-----------------------
1. **Download Python**:
   - Visit the official [Python website](https://www.python.org/downloads/).
   - Download the latest stable version for your operating system.

2. **Install Python**:
   - Run the installer and ensure the following options are selected:
     - "Add Python to PATH" (very important).
     - "Install pip" (this is usually included by default).

3. **Verify Installation**:
   - Open a terminal (Command Prompt, PowerShell, or Bash) and run:
     ```bash
     python --version
     pip --version
     ```

Step 2: Install Git
-----------------------
1. **Download Git**:
   - Visit the official [Git website](https://git-scm.com/).
   - Download and install Git for your operating system.

2. **Verify Installation**:
   - Open a terminal and run:
     ```bash
     git --version
     ```

Step 3: Install Visual Studio Code (Optional but Recommended)
-----------------------
1. **Download VS Code**:
   - Visit the official [VS Code website](https://code.visualstudio.com/).
   - Download and install VS Code for your operating system.

2. **Install Python Extension**:
   - Open VS Code.
   - Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
   - Search for "Python" and install the official Microsoft Python extension.

Downloading and Setting Up FARM-VSS
-----------------------------------

### Step 4: Clone the Repository

1. **Open a Terminal**:
   - Navigate to the directory where you want to clone the repository.

2. **Clone the FARM-VSS Repository**:
   ```bash
   git clone https://github.com/yourusername/farm-vss.git
   cd farm-vss
