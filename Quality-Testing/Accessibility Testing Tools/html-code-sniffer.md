# HTML_CodeSniffer

## 1. Introduction of HTML_CodeSniffer
HTML_CodeSniffer is a client-side script that checks HTML source code and detects violations of a defined coding standard. HTML_CodeSniffer is written entirely in JavaScript, does not require any server-side processing and can be extended by developers to enforce custom coding standards by creating your own "sniffs".

## 2. Using HTML_CodeSniffer
HTML_CodeSniffer can be called in multiple ways:

* Called directly in JavaScript source, HTML_CodeSniffer will provide a list of known and potential violations to the calling script.
* It also comes with a pop-up auditor interface, accessible via a bookmarklet, letting you browse through messages emitted from one of the defined standards. Where possible, the auditor also points you to the HTML element causing the problem.
* It can also be run on the command line with the assistance of a headless browser app.
* Using as a Node.js module, installed with npm: npm i --save html_codesniffer

## 3. Demo test website http://hoclieu.sachmem.vn
This demo use the HTML_CodeSniffer on the bookmarklet.
1. Go to: https://squizlabs.github.io/HTML_CodeSniffer/
2. Click and drag the link "Get the Accessibility Auditor Bookmarklet" to your browser bookmarkbar.
3. Go to: http://hoclieu.sachmem.vn
4. Click the link "HTML_CodeSniffer" on the bookmarkbar and the tool will run.

## 4. Youtube tutorial
Link: https://youtu.be/fxupjYzdHm4
