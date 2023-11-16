# translit_keyboards
## About 
This is a keyboard layout for inputing Ancient Egyptian transliterations in unicode.
When installed, you will be able change the keyboard on your computer to input Ancient Egyptian transliteration unicode characters, just like you can change it to input Cyrilic, Arabic, Chinese or any other script.  This keyboard layout was designed to be intuitive to people who already use Manual de Codage or the Trilit_CG True Type font to type transliteration.

## Installation
### Mac
The Mac version was created with [Ukelele](https://software.sil.org/ukelele/). If you have an older version of MacOS, you can use the DMG file to install it (I'm not sure when this feature broke with Ukelele. I know that it does not work with Ventura, but did when I made the first version of the keylayout three years ago). If you have a newer version of MacOS, such as Ventura, you should follow the instructions for installing the Keylayout file. IF the instructions for the DMG file don't work, use the "Installing from the Keylayout File" instructions.
#### Installing from the DMG file (Sierra(?) and older)
* To use the DMG file, download  [Egyptian Translit.dmg](https://github.com/nanythemummy/translit_keyboards/blob/main/Mac/Egyptian%20Translit.dmg).
* Double click to open it. If MacOS asks you if you would really like to open a program from the internet, click yes. You should see a window with a keylayout file and a file called "Keyboard Installer"
* Click "Keyboard Installer"
* Drag and drop the "Egyptian Translit.keylayout" from the DMG window in step 2 to the Keyboard installer window and click "Install for Current User".
* This should install the keyboard, but you still need to add it to Mac's keyboard list. You should restart your computer and then proceed to the instructions for Enabling the Keyboard.

#### Installing from the Keylayout File (PREFERRED METHOD)
* To install, download [Egyptian Translit.keylayout](https://github.com/nanythemummy/translit_keyboards/blob/main/Mac/Egyptian%20Translit.keylayout)
* CTRL+Click on the finder icon on your dock at the bottom of the screen so that a context menu pops up.
* In this Context Menu, click "Go To Folder"
* Type "/Library/Keyboard Layouts" (without the quotes) and hit enter.
* Copy "Egyptian Translit.keylayout" to this folder.
  * When MacOS asks you to enter the computer password do it.
  * If you don't have the password, you can try to copy it to your local user library folder: go to the folder "~/Library/Keyboard Layouts" and copy the file there instead. 
*  Restart your computer, then follow the instructions for Enabling the Keyboard.

#### Enabling the Keyboard, MacOS
* To finish installing the keyboard, go to preferences by clicking the little icon of a gear down in your dock.
* Then, click the "Keyboard" button
* In the pane on the right side of the screen, there should be a section  for "Text Input" about halfway down.
    * Next to "Input Sources", click the "Edit" button.
    * Make sure the option to "Show Input menu in menu bar" is enabled.
    * Then, click the little plus button down in the lower left hand corner of the screen to install the new keyboard.
    * You will get a list of languages you can install. If you scroll down to "Others", "Egyptian Translit" should be in the list.
    * Select it and then click the "Add" button.

#### Switching to and from Egyptian Translit Input (MacOS)
* If you enabled the "Show Input menu in menu bar" Option in the "Enabling the Keyboard" section, you should see a keyboard menu next to your clock on the upper right side of the screen. Mine says "U.S." (For US English).
* You can click it and it will give you input options. Select "Egyptian Translit" to switch to inputing Egyptian Translit.
* Now, just type transliterated text like you would enter it in Manuel de Codage.
* If you want to switch back to your normal alphabet, click the button up by the clock again and switch it back.

## Tips
1. If you see little boxes where your characters should be, it means you are using a font that doesn't support the unicode character you're using. There are a lot of fonts that support Egyptian Transliteration, but I recommend:
* [New Athena](https://classicalstudies.org/publications-and-research/nau-download)
* [Gentium Plus](https://software.sil.org/gentium/)

2. I recently added the new character in the [Leiden Unified Transliteration](https://ice2023.com/en/news/lut).
   * For ï, use shift+i
3. For those attached to ḳ instead of q, use shift+k
4. Demotic people can use the v-key for ṱ
5. To see all the mappings on mac, go to the input dropdown near the click "Show Keyboard Viewer.

## Bugs and Other Known Issues
1. These keyboards don't support capital letters. The old Trilit_CG font used to solve this problem by replacing numbers with capital versions of ḤḪH̱ etc, but I felt that being able to enter numbers was a lot more important--I don't see caps in a lot of typed transliterations anyway.
   
## Feedback
If you have any problems, drop me an email at kjohnsto@berkeley.edu

  






