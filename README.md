# **Installation Instructions**

## To install this code, follow these steps:

### PC Instructions(Extension):

1. Download most recent .zip file from _"versions"_ tab on right

2. Select the .zip folder, right click and select _"unzip"_ or _"extract all"_

3. Go to the _extensions_ page by clicking the extensions puzzle piece icon on the top right and clicking "_manage extensions_"

4. Make sure that devloper mode is turned **ON** by clicking the slider on the top right

5. Select _"Load unpacked"_, and select the _extracted_ zip folder by double clicking it and clicking Select Folder. It will probably be named Source Code.

### IOS or other browser instructions (Script)

1. Install something like _TamperMonkey_ on your device, such as _Stay for IOS_

2. Follow any instructions that _Stay_ or whatever you have gives you

3. Go to the "UserScript" file (above) and copy all contents

4. Following your chosen application's instructions, paste it into the userscript field, replacing all existing contents that may exist in that field.

## **Usage Instructions**

This code will automatically replace user-defined shortcuts in the CodeHS editor with a user - defined code segment. 

To start, click on the extension icon. Three fields will appear:

_Shortcut field:_ This is where you can add the shortcut that wiil get replaced. If you want to automatically replace _"sopl"_ with _"System.out.println();"_, this is where you would add _"sopl"_.

_Replacement field:_ This is where you can add the replacement for the shortcut. In the previus example, this is where you would add the _"System.out.println();"_ part.

_End Offset field:_ If you want the cursor to not go to the end when you replace the text, you can change this value. In our case, if you want the cursor to go between the two parentheses when _"System.out.println();"_ is added, you can set this value to                 "2", since the middle of the parentheses is 2 away from the end of the String.
