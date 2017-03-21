# Swift Templates for Visual Studio
**Version 0.1**

## Getting Started
This project enables Visual Studio users on Windows to copmile and execute Swift programs.

## Download the latest release
Download the latest release from the [Releases](https://github.com/svetoslav-maksimov/SwiftForVisualStudio/releases) page.
You can install the extension to Visual Studio using the .vsix file. Restart of Visual Studio will be required in order to see the new  templates.

## Prerequisites

### Install swift for windows
The project is based on [https://swiftforwindows.codeplex.com](https://swiftforwindows.codeplex.com). You can download the latest package from there.
1. Download SwiftForWindows from [https://swiftforwindows.codeplex.com](https://swiftforwindows.codeplex.com)
2. You can install SwiftForWindows via the installer, but it's not a hard recommendation. You can just extract the content of WinRoot\SwiftForWindows into a folder on your local machine, e.g. D:\swiftForWindows
3. Add the binaries path of SwiftForWindows (e.g. D:\SwiftForWindows\Swift\bin) to your local %PATH% variable.
4. Restart Visual Studio so that it re-reads the %PATH% variable.

## Creating a new project
1. Once you have installed the extension, you will be able to create a new Swift project in Visual Studio.
2. Select File -> New -> Project, and search for the SwiftForVisualStudio project template. Create your project using this template.
3. Edit SwiftBuild.targets in your project. Make sure that paths are correct in this file.
4. You can now start editing main.swift

 ## Run and debug
To run the project, press Ctrl+F5. Visual Studio will:

* Compile the swift code.
* If any compile errors occur, they will be displayed in Visual Studio Errors window.
* Link object files to a Windows executable
* Start the generated executable.

**Note: Debugging is not supported in this version of Swift For Visual Studio**


## Demo
[See a demo video](https://github.com/svetoslav-maksimov/SwiftForVisualStudio/blob/master/swift-for-vs-0-1.mp4)
            
## Additional resources
* [SwiftForWindows](https://swiftforwindows.codeplex.com/)
The swift compiler build for Windows, used in this project.

* [Syntax Highlighting Pack](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.SyntaxHighlightingPack)
Useful extension for syntax highlighting with Swift support.

* [Swift language](https://developer.apple.com/swift/)The official page of the Swift language.
