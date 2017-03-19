# Swift Templates for Visual Studio
**Version 0.1**

## Getting Started
This project enables Visual Studio users on Windows to copmile and execute Swift programs.
### Install swift for windows
The project is based on [https://swiftforwindows.codeplex.com](https://swiftforwindows.codeplex.com). You can download the latest package from there.
1. Download SwiftForWindows from [https://swiftforwindows.codeplex.com](https://swiftforwindows.codeplex.com)
2. You can install SwiftForWindows via the installer, but it's not a hard recommendation. You can just extract the content of WinRoot\SwiftForWindows into a folder on your local machine, e.g. D:\swiftForWindows
3. Add the binaries path of SwiftForWindows (e.g. D:\SwiftForWindows\Swift\bin) to your local %PATH% variable.
4. Restart Visual Studio so that it re-reads the %PATH% variable.
5. Edit SwiftBuild.targets in your project. Make sure that paths are correct in this file.
6. You can now start editing main.swift

 ### Run and debug
To run the project, press Ctrl+F5. Visual Studio will:

* Compile the swift code.
* If any compile errors occur, they will be displayed in Visual Studio Errors window.
* Link object files to a Windows executable
* Start the generated executable.

**Note: Debugging is not supported in this version of Swift For Visual Studio**
            
            
## Resources
* [SwiftForWindows](https://swiftforwindows.codeplex.com/)
The swift compiler build for Windows, used in this project.

* [Syntax Highlighting Pack](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.SyntaxHighlightingPack)
Useful extension for syntax highlighting with Swift support.

* [Swift language](https://developer.apple.com/swift/)The official page of the Swift language.