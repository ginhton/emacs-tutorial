# emacs tutorial
## what is emacs?
An old but powerful editor.
## installation
### windows
1. go to the [main page](https://www.gnu.org/software/emacs/). Click windows button.
<img src="pic/main-page.png">
2. click the "nearby GNU mirror".
<img src="pic/windows-download-link.png">
3. select the version you like. for example, "emacs-26".
<img src="pic/select-page-1.png">
4. select one file you want to download. for example, "emacs-26.1-x86_64.zip".
<img src="pic/select-page-2.png">
5. after downloading, unzip that file.
6. run "runemacs.exe".

### MacOS
1. download from [emacs for macosx](https://emacsformacosx.com/).
2. install.

### Linux
1. simple method: `sudo apt-get install emacs`
2. the other: 
   - go to http://gnu.mirror.globo.tech/emacs/ .
   - download package, extract it and compile.

## learning materials
* inside the editor : press F1 t. Then follow the instructions.
* [online mannual](https://www.gnu.org/software/emacs/manual/html_node/emacs/index.html)
* [emacs is sexy](http://emacs.sexy/)

## operation
### basic key
* C means Ctrl
* M means Alt (Windows, Linux), Command (MacOS)
* S means Shift
* C-a mean press Ctrl and a at the same time. 

### file
* open : C-x C-f
* save : C-x C-s
* close : you don't need to close a file. just open another file and edit.

### move
* move to previous line: C-p
* move to next line: C-n
* move backwords: C-b
* move forwards: C-f

### exit
* exit editor : C-x C-c
* exit current command : C-g

### window
* split window vertically : C-x 2
* split window horizontally : C-x 3
* delete current window : C-x 0
* delete other windows : C-x 1
* jump to other window : C-x o

### buffer
* buffer list : C-x C-b
* switch buffer : C-x b buffer-name
* open buffer in another window : C-x 4 b buffer
* previous buffer : C-x <LEFT>
* next buffer : C-x <RIGHT>

## configuration
* The configuration file in emacs is `.emacs`.  When you want to modify some settings, you can find this file.
* Location
  - windows: C:\Documents and Settings\\`(yourname)`\Application Data\.emacs
  - Linux / MacOS: ~/.emacs
* The configuration file is made up of Lisp code.  So you can use 10 min to learn Lisp by view this [site](https://learnxinyminutes.com/docs/elisp/).

## org mode
* org is a file format, for example, `1.org` or `date.org`.  mode is a emacs editor environment for a specific format, such as `c mode` for C or `python mode` for python.

* create an org file: C-x C-f, then input file path: such as `./test.org`.

* list example (you can copy lines below to your `test.org` or other org file)
```org-mode
* this 1-level title
** this 2-level title
*** this 3-level title
* this 1-level title
* TODO this is a todo item
  - list item 1
  - list item 2
  - list item 3
  - [ ] list item with checkbox (todo)
  - [X] list item with checkbox (done)
```
  - [list practice](practice/list.org)

* important command
  - Tab : fold / unfold a title
  - M-<LEFT> / M-<RIGHT> : increase or decrease level of title and list item
  - M-<UP> / M-<DOWN> : move title or list item upwards or downwards with its content
  - C-c C-t : toggle title status. TODO -> DONE -> none -> TODO ...
  - C-c C-s : shedule for an item
  - C-c C-d : dealine for an item
  - M-x org-agenda a : open org-agenda view

* workflow
  - org-capture
  - org-refile
  - edit
  - archive

* org reveal.js
TODO


## tutorial
* inside emacs, press`C-h t`, and then follow the instructions
* [Chinese traslate of previous tutorial](https://zhuanlan.zhihu.com/p/27299756)
* 陈斌的 *Master Emacs in One Year*
* *Mastering Emacs*
* other online blog, for example, CSDN.

## exercise
### simple operations
TODO
### list operations
TODO
### org mode
TODO


## other distributions
TODO
### spacemacs
TODO

## FAQ
* If you have any questions, you can just leave an issue or send me a msg.
