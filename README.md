# Python't
An esoteric programming language based on Python

Start with normal Python code. Each letter then gets replaced with its inverse (e.g. "a" is replaced with "z", "C" is replaced with "X", "8" is replaced with "1"). Any character which is not alphanumeric stays unchanged. Then the order of the lines is reversed.

## Usage
usage: pythont.py [-h] [--output OUTPUT] [--bin BIN] [--noexec] [--nocleanup] src [args [args ...]]

positional arguments:<br />&nbsp;&nbsp;src&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;path to the script you want to transpile.<br />&nbsp;&nbsp;args&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; arguments to pass to the transpiled script upon execution

optional arguments:
<br />&nbsp;&nbsp;-h, --help
<br />&nbsp;&nbsp;&nbsp;&nbsp;show this help message and exit

&nbsp;&nbsp;--output OUTPUT
<br />&nbsp;&nbsp;&nbsp;&nbsp;path to store the transpiled code (default is the same name as the src file with a '.py' extension)

&nbsp;&nbsp;--bin BIN
<br />&nbsp;&nbsp;&nbsp;&nbsp;path to the Python binary to execute the script (default is 'python3')

&nbsp;&nbsp;--noexec
<br />&nbsp;&nbsp;&nbsp;&nbsp;only transpile the code, do not execute it

&nbsp;&nbsp;--nocleanup
<br />&nbsp;&nbsp;&nbsp;&nbsp;do not delete transpiled code after execution
