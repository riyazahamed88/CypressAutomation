# CypressAutomation
#Cypress Step by Step Installation
# Node.js Setup Guide

## What is Node.js?
Node.js is an open-source, cross-platform, backend JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside of a web browser. It allows developers to use JavaScript for server-side scripting, enabling the creation of dynamic web pages and applications.

## Download Node.js

To download Node.js for Windows, follow these steps:

1. **Visit the Node.js Website:**  
   Go to the official Node.js website at [nodejs.org](https://nodejs.org).

2. **Download the Installer:**  
   You'll find two versions available for download: **LTS (Long-Term Support)** and **Current**. The LTS version is generally recommended for most users. Click on the Windows installer (`.msi`) for the version you prefer.

3. **Run the Installer:**  
   Once the download is complete, open the installer file.

4. **Follow the Installation Wizard:**
   - Click “**Next**” on the welcome screen.
   - Accept the license agreement and click “**Next**.”
   - Choose the installation directory or leave it as the default and click “**Next**.”
   - On the “**Select Components**” screen, leave the default selections checked and click “**Next**.”
   - Ensure “**Add to PATH**” is selected so you can run Node.js from the command line, and click “**Next**.”
   - Click “**Install**” to begin the installation.

## Verifying the Installation

After installation, verify that Node.js is installed correctly:

1. Open the Command Prompt (CMD) or PowerShell.
2. Type the following command to check the Node.js version:
   ```bash
   node -v
#Set the path for nodejs


# How to Add or Modify a System Variable in Windows

## Introduction
This guide provides step-by-step instructions on how to add or modify system variables in Windows 10 and Windows 11.

## Steps to Add or Modify a System Variable

### 1. Open System Properties
- Right-click on the Start menu and select “**System**.”
- In the System window, click on “**Advanced system settings**” on the left side.

### 2. Open Environment Variables
- In the System Properties window, click the “**Environment Variables**” button near the bottom.

### 3. Edit System Variables
- In the Environment Variables window, you'll see two sections: "User variables" and "System variables."
- To add a new system variable, click the “**New**” button under the "System variables" section.
- To edit an existing system variable, select it from the list and click “**Edit**.”

### 4. Add or Modify the Variable
- **To Add a New Variable:**
  - Enter the variable name and value in the provided fields and click “**OK**.”
- **To Modify an Existing Variable:**
  - Change the variable name or value as needed and click “**OK**.”

### 5. Apply Changes
- Click “**OK**” in the Environment Variables window to save your changes.
- Click “**OK**” again in the System Properties window to close it.

### 6. Restart Applications
- For changes to take effect, you might need to restart any applications or the system that were open when you made the change.

## Example: Adding a New System Variable

To add a new system variable called `MY_VAR` with the value `C:\MyPath`:

1. Click “**New**” under System variables.
2. Enter `MY_VAR` as the **Variable name**.
3. Enter `C:\MyPath` as the **Variable value**.
4. Click “**OK**” to save.

Now, `MY_VAR` will be available as a system variable that can be used by applications and scripts.
## Verify Installation

1. **Open Command Prompt:**
   - Search for `cmd` in the Start menu and open the Command Prompt.

2. **Check Node.js Version:**
   - Type the following command and press Enter:
     ```bash
     node -v
     ```
   - This should display the version of Node.js installed on your machine.

3. **Check npm Version:**
   - Type the following command and press Enter:
     ```bash
     npm -v
     ```
   - This should display the version of npm (Node Package Manager) installed on your machine.

That's it! Node.js should now be installed on your Windows machine.
## Step 1: Create a New Project with `package.json`

1. **Open Visual Studio Code:**
   - Launch Visual Studio Code on your computer.

2. **Open Terminal:**
   - Click on the `Terminal` option in the top menu and select `New Terminal` to open a terminal window within Visual Studio Code.

3. **Create the Project Directory:**
   - Use the following command to create a new directory for your project:
     ```bash
     mkdir CypressAutomation
     ```
   - Navigate to the newly created directory:
     ```bash
     cd CypressAutomation
     ```

4. **Initialize the Project:**
   - Run the following command to create a `package.json` file in your project directory:
     ```bash
     npm init -y
     ```
   - This command initializes a new Node.js project and automatically creates the `package.json` file with default settings.

## Step 2: Install Cypress in Windows

1. **Install Cypress via npm:**
   - To install Cypress, run the following command in the terminal:
     ```bash
     npm install cypress --save-dev
     ```
   - This command installs Cypress as a development dependency in your project.

2. **Verify Cypress Installation:**
   - After the installation is complete, verify the Cypress version by running the following command:
     ```bash
     npx cypress version
     ```
   - This command will display the installed version of Cypress, confirming that the installation was successful.

## Additional Notes
- The `package.json` file contains metadata about your project, such as the project name, version, dependencies, and scripts.
- Cypress is a powerful tool for end-to-end testing, making it easier to write and run tests for your web applications.

---
