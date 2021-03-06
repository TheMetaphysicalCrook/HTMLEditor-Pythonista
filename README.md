[![Travis.CI-BuildStatus](https://travis-ci.org/Cethric/HTMLEditor-Pythonista.svg?branch=master)](https://travis-ci.org/Cethric/HTMLEditor-Pythonista/builds)
# HTMLEditor-Pythonista
A basic html editor for the pythonista app
This is a complete rewrite of the code paying attention to the suggestions and improvements by cclauss

### Features to include
+ [ ] Builtin Customizable lan server
+ [x] ~~Code checker for html, css and js (HTML, JS, CSS are done)~~ this is done by CodeMirror
+ [x] ~~Builtin page previewer~~ Finished for HTML only
+ [ ] Dropbox, Onedrive, GoogleDrive, FPT and other cloud based file management services to be incoorperated.
+ [x] Ability to save to zipfile
+ [ ] Send webfiles from iDevice to a computer (possibly as a zip and intergrated HTTP server).

### TODO
+ [ ] Code clean up
+ [ ] Work on the server side (Thank you [Gerzer](https://github.com/Gerzer))
+ [ ] Make the editor a litle but more reliable

### HTML Editor Features
+ ~~HTML tag completions~~ CodeMirror might not do this...
+ HTML quick previewer
+ ~~HTML code checking~~ CodeMirror might not do this...
+ Syntax Highlighter - Done Through CodeMirror


### Server Editor Features
+ Yet to be done.


### KNOWN BUGS
+ ~~Opening a file usually doesn't work, the file gets overwritten before display causing major issues (issue #12)~~
+ The close button sometimes hangs requiring an app restart (issue [#13](https://github.com/Cethric/HTMLEditor-Pythonista/issues/13)) (RE-OPENED :( )
+ ~~Opening a file disables the ui.Webview (issue [#18](https://github.com/Cethric/HTMLEditor-Pythonista/issues/18))~~
+ Adding a tag through the tag insert system may overwrite all of the open files (issue [#24](https://github.com/Cethric/HTMLEditor-Pythonista/issues/24))
+ Themes are not correctly applied to ui.TableView and ui.TableViewCells (issue [#25](https://github.com/Cethric/HTMLEditor-Pythonista/issues/25))
+ Themes sometimes have incorrect background colour (issue [#26](https://github.com/Cethric/HTMLEditor-Pythonista/issues/26))
