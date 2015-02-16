# iLasse Module

## Description

Fix for the iOS 8.1 bug causing UIWebView to crash when tapping a <select> several times.

Description/solution here: http://stackoverflow.com/questions/25908729/ios8-ipad-uiwebview-crashes-while-displaying-popover-when-user-taps-drop-down-li

## Accessing the iLasse Module

No need to instantiate. The module overrides existing classes TiViewController and TiRootViewController.

## Reference

-

### ilasse.function

-

### ilasse.property

-

## Usage

var webView = Ti.UI.createWebView({url: "http://www.w3schools.com/tags/tryit.asp?filename=tryhtml_select"});
$.index.add(webView);
$.index.open({modal: true});

## Author

Accelerait 2015

## License

The MIT License (MIT)

Copyright (c) 2015 Accelerait

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
