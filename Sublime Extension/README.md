This Extension is an adoption of OpenURL sublime extension with required modification.

FaCoY extension for Sublime Text Editor:

Team No. 1
Team Members:
  Ashutosh Rajput (CS17B007)
  K.S.Koushik (CS17B013)
  Nakshatra Gupta (CS17B020)

------------------------------------------------------------------------------------------

Description : 

FaCoY is a very cumbersome application to use.
It works on a virtual machine (Linux based)
There is no graphical interface to start the application.
You need to access the proper directory in the terminal.
Then, you need to write complex commands to start FaCoY on localhost.
There was no way you could access FaCoY from a text editor.

This extension allows you to start FaCoY from sublime text 
using shortcut-key sequence "ctrl+alt+f"

This will start FaCoY on "http://0.0.0.0:5000/"

Now, when the application has started,

If you want to search for a code snippet on FaCoY,
just select the snippet, press the shortcut-key sequence "ctrl+alt+u".

A command-pallete menu will appear on the screen.

Select "FaCoY search ---> " option.

The whole code snippet will be automatically sent to "http://0.0.0.0:5000/?q=".

This will result in a url ""http://0.0.0.0:5000/?q= _code-snippet_"

FaCoY will search for similar snippets in its database and produce the result.

------------------------------------------------------------------------------------------

The required files are uploaded in the repository, you need to manually add these files to sublime-text installed packages.


