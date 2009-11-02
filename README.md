Quicktime/MP4 Rotation Tools
============================
Tools to work with rotated Quicktime/MP4 files. Currently this consists of a tool to detect and return the rotation angle if one can be found. Once known, you can use the info to rotate the video using MEncoder's rotate filter, AviSynth, etc.

Patches and new tools welcome.

Simple Usage
------------
The script is usable as both a Python library and a standalone script:

    $ ./qtrotate.py myfile.mp4
    90

License
-------
Copyright (c) 2008 - 2009 Daniel G. Taylor <dan@programmer-art.org>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
