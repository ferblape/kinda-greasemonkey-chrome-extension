# Kinda Greasemonkey Boilerplate Chrome Extension

The purpose of this boilerplate is to show you that is really easy create simple extensions
for Google Chrome that executes javascript code in the page(s) you specify in the manifest.

In the `manifest.json` file you'll find two files, one is jQuery 1.7.1 minified and the other
contains a basic JS file named `extension.js` where you can start writing your code. Doing things
like modifying the DOM is really simple with jQuery.

## How to use it

1. Clone the repo to your local machine

```shell
git clone https://github.com/ferblape/kinda-greasemonkey-chrome-extension.git
```

2. Start developing your own extension

## How to install your extension in development mode

1. Open Chrome

2. Bring up the extensions management page by clicking the wrench icon and choosing __Tools > Extensions__.

3. If __Developer mode__ has a + by it, click the + to add developer information to the page. The + changes to a -, and more buttons and information appear.

4. Click the button with the name of the extension. A file dialog appears.

5. In the file dialog, navigate to your repo's folder and click OK

6. Browse to the domain where your extension is configured to work

7. If the extension is valid, you can open the console of the Javascript Developer tools and you'll see a message.

8. Notice that any change in the files of your extension require you to reload it. You can use Cmd + R
shortcut.

## Thanks

- @pacoguzman for his extension [Lolcommits](https://github.com/pacoguzman/lolcommit_github_chrome_extension), from
which I got the idea (and the code).

## Source Code License(s)

All source code in this project are licensed under the MIT license.

Copyright (c) 2012.

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
