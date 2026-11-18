# How to Install Chill Mars Tower Defense

Follow the instructions below to download and run the game on Windows.

### Requirements
- Windows 10 or 11
- Node.js installed
- Internet connection

### 1. Install Node.js

Download Node.js from https://nodejs.org/

Choose the LTS version and run the installer. You can leave the installation settings as they are.

### 2. Download the game

1. Open this GitHub repository.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Once downloaded, right-click the ZIP file and select **Extract All**.
5. Open the extracted folder.

### 3. Install the required files

Open the game folder.

Click the folder's address bar, type `cmd`, and press Enter. This opens a command window in the correct location.

Enter:

```bash
npm install
```

Wait for the installation to finish.

### 4. Start the game

In the same command window, enter:

```bash
npm start
```

The game should open in its own window.

### Building a Windows installer

You can also build an installer instead of launching the game through the terminal.

1. Open the game folder.
2. Find `BUILD_WINDOWS.bat`.
3. Double-click the file.
4. Wait for the build process to finish.
5. The installer should appear inside the newly created `dist` folder.

### Troubleshooting

**'npm' is not recognized**

Make sure Node.js is installed. Restart your computer and try again.

**The game won't start**

Run `npm install` again and check that there are no installation errors before running `npm start`.

**Installation is failing**

Make sure you are running the commands inside the extracted game folder, not the ZIP file itself.

---

Chill Mars Tower Defense is still being developed. Updates, new content, and improvements will be added as development continues.
