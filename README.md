# frontend-utils
A repo with utils regarding Frontend Development

> **Node.js** is a run-time environment which includes everything you need to execute a program written in JavaScript. It’s used for running scripts on the server to render content before it is delivered to a web browser.

> **NPM** stands for Node Package Manager, which is an application and repository for developing and sharing JavaScript code.

> **Visual Studio Code** is a lightweight but strong source code editor that runs on your desktop and is available for Windows, macOS, and Linux. VSC has built-in support for JavaScript, TypeScript, and Node.js.

> **VS Code Extension Marketplace** The features that Visual Studio Code includes out-of-the-box are just the start. In addition, VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow.


## Windows

### Install Node.js and NPM

**Step 1: Download Node.js Installer**

In a web browser, navigate to https://nodejs.org/en/download/. Click the Windows Installer button to download the latest default version. The Node.js installer includes the NPM package manager.

**Step 2: Install Node.js and NPM from Browser**

Once the installer finishes downloading, launch it. Click Run, You will be welcomed to the Node.js Setup Wizard – click Next and install it. 

**Step 3: Verify Installation**

Open a command prompt (or PowerShell), and enter the following:
```shell
node -v
```
The system should display the Node.js version installed on your system. You can do the same for NPM:
```shell
npm -v
```

### Install Visual Studio code

**Step 1** : Download VS code for Windows from here [Link](https://code.visualstudio.com/download).

**Step 2** : Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute

**Step 3** : After accepting all the requests press finish button. By default, VS Code installs under: “C:\users{username}\AppData\Local\Programs\Microsoft VS Code.




## Mac OS

### Install Node.js and NPM

**Step 1: Download Node.js Installer**

Navigate to https://nodejs.org/en/download/. Download Node.js for macOS by clicking the "Macintosh Installer" option. It includes the NPM package manager as well.

**Step 2: Install Node.js and NPM**

Run the downloaded Node.js .pkg Installer, including accepting the license, selecting the destination, and authenticating for the install.

**Step 3: Verify Installation**

To verify that Node.js was installed correctly on your Mac, you can run the following command in your terminal:
```shell
node -v
```
The system should display the Node.js version installed on your system. You can do the same for NPM:
```shell
npm -v
```

### Install Visual Studio code

**Step 1** : Download VS code for Mac from here [Link](https://code.visualstudio.com/download).

**Step 2** : Double-click on the downloaded archive to expand its contents.

**Step 3** : Drag Visual Studio Code.app to the Applications folder, making it available in the Launchpad.

**Step 4** : Add VS Code to your Dock by right-clicking on the icon to bring up the context menu and choosing Options, Keep in Dock.




## Usefull commands

**How to install extensions in VScode**

Simply type cmd + shift + x (on a Mac) or ctrl + shift + x (on a PC) to bring up the View: Extensions panel or Open the “Extensions” sidebar. 
Type and search any extension, select and install it.  

> Recommended extension to VS Code: - Angular Language Service - TS Lint (Microsoft version)

**Upgrading to the latest version of npm**

```shell
npm install npm@latest -g
```



