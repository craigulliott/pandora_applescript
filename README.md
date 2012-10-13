pandora_applescript
===================

This is used as part of my smart home.  It is an small apple script which can be used from the command line.  It can open, login, logout, play pause and set the station of Pandora.

Usage
-----
```
osascript pan.scpt "your email" "your password" <true/false : open pandora if not already open> <command> <station : if command was "station">

examples:

osascript pan.scpt "your email" "your password" true open
osascript pan.scpt "your email" "your password" true pause
osascript pan.scpt "your email" "your password" true station "Ellie Goulding"
osascript pan.scpt "your email" "your password" false close
```

Developers
----------

To view or modify the source, open it on your mac with "AppleScript Editor"

Licence
-------

Copyright (c) 2012 Craig Ulliott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

