# VisualStudioTools

## How to Use

1. Open your Visual Studio solution
2. View > Property Manager
3. Right click on your application or dll and select "Add Existing Property Sheet"
4. In the file browser, navigate to this repo
5. If you are:
    - Building a DLL using LibraryLink, select LibraryLink.props
    - Building a binary using MathLink, select MathLink.props
    - Building a binary using WSTP, select WSTP.props

This is setup to use the default installation directory for Mathematica 12.1.  If you wish to alter this:

1. Click on the arrow to the right of the property sheet you added until you see VersionInformation
2. Double click on VersionInformation
3. Select User Macros in the list on the left
4. If you just:
    - Want to change the version number, double click on WolframVersionNumber
    - Modify the complete path, double click on WolframInstallationDirectory
5. Click Apply when finished.
6. You might need to close your solution and reopen it

