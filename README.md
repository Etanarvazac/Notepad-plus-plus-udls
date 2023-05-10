# Notepad++ User Defined Languages Collection
This is a collection of User Defined Languages (UDL's) all in one place! All of which are packed in 1 file or individually using the content list below. Each directory contains a ReadMe with the author and other information that may prove useful. For instructions on how to install, see ![#Installation Instructions](https://github.com/Etanarvazac/Notepad-plus-plus-udls#Installation-Instructions).

## Table of Contents
<table>
  <tr>
    <td align="center"><b>Categories</b></td>
    <td align="center"><b>Topic</b></td>
    <td align="center"><b>Items</b></td>
  </tr>
  <tr>
    <td rowspan=2 align="center">Games</td>
    <td rowspan=2 align="center">Minecraft</td>
    <td>Output Logs</td>
  </tr>
  <tr>
    <td><b>.mcfunction</b> files</td>
  </tr>
</table>

## Installation Instructions
1. Open the `userDefinedLangs` folder by opening Notepad++ and navigating on the top menu to: `Languages > User Defined Language > Open User Defined Language Folder`
2. If you downloaded the all-in-one pack, unzip the ZIP file and copy all of the XML files into this folder. Otherwise, you'll need to create the individual file to paste the code into. You'll first create a text document and rename it to `<languageNameHere>.xml`. On Windows, you'll have to turn on `File name extensions` under the `View` ribbon.
3. Right-click the XML file and select `Edit` to open the file in your default text editor
4. Copy the XML code you want to install into Notepad++ and paste it into the document. Save and close the editor.
5. In Notepad++, navigate to `Language > User Defined Language > Define your language...` and click `Import`
6. You should now see the XML file you just created. Click it and then `Open`
7. Once imported, click the dropdown, `User language:` and select the one you just imported.
8. Click `Save As...` and name it something easily remembered.
9. Close the window and return to Notepad++. Your language should now be at the bottom of the `Language` top menu item.

## Contributions
Contributions are very much accepted to make this library of UDL's as large as possible. Follow the guidelines below and your submission should be approved.
- Your submission MUST be readable. If it's readable only in a dark Notepadd++ theme, you need to note that or provide a light theme varient with both versions noted for which is which.
- IF you are submitting for a game, you need to note what game in the submittion. For example, the way Minecraft logs is different to how Fallout 4 would log.
- IF your app or game has a seperate file type, you need to note the file extension in the submittion. For example, Minecraft has `.mcfunction` which wouldn't be used by another app or game.
- IF your app or game uses a common file type differently and your submission highlights that difference, note it. For example, Minecraft's use of `.json` could include game functions/commands which have their own syntax for.
- IF your submission does indeed further highlight a common file type (e.g.: `json`, `yml`, etc.), do NOT set the file extension parameter. For example, `.json` is already defined built-in, so your file shouldn't argue with it.
