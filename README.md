version https://git-lfs.github.com/spec/v1
oid sha256:4b7f8d661862e6cef0bd8456dbf31f8a331f2d657bfa9255243d0a974403c635
size 60


How to Use the Tool
Fill out Application Information: Enter your app's name, version, publisher, and website. This info appears in the installer and in the Windows Control Panel.
Select Languages:
In the "Languages" section, you'll see a list of common languages.
Click to select one language.
Hold Ctrl and click to select multiple languages.
Hold Shift and click to select a range of languages.
The user will be prompted to choose one of your selected languages when they start the installer. English is selected by default.
Choose Files and Paths:
Main Executable: This is mandatory. Click "Browse..." to select your application's main .exe file.
Setup Icon (Optional): Select an .ico file to be used as the icon for the setup file itself.
License File (Optional): Select a .txt or .rtf file containing your license agreement.
Configure Installer Settings:
Output Directory: Choose the folder where the final setup.exe will be saved. Your Desktop is the default.
Installer Filename: Name your setup file (e.g., MyCoolApp_Installer).
Set Options:
Check the boxes if you want to create shortcuts on the desktop and/or in the Start Menu.
Generate the Script:
Click the big blue "Generate .iss Script" button.
A "Save As" dialog will appear. Choose a name and location for your .iss file.
The tool saves the complete script to this file.
Next Steps: Creating the Installer
After the Python tool has created your .iss file:
Open the Inno Setup Compiler.
Go to File -> Open... and select the .iss file you just saved.
You will see all the generated code in the Inno Setup editor.
Click Build -> Compile (or press F9).
Inno Setup will compile the script and create your final setup.exe in the output directory you specified.
Done! You now have a professional, multi-language installer for your application.
