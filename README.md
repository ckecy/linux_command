## Linux Command ##

在**MatLab**我們有**help**和**lookfor**，**Linux**也有類似的指令，有以下三種方式: 
- `man 指令`
- `info 指令`
- `指令 --help`

- 忘記指令: 善用Tab鍵

### 一、絕對路徑和相對路徑 ###

- 絕對路徑: 只要是由根目錄`/`寫起，就是絕對路徑的表示法
- 相對路徑: 不是由根目錄`/`寫起，就是相對路徑的表示法

- `.`: 目前自己所在的目錄
- `..`: 目前自己所在的這個目錄得上一個目錄


**注意**:

絕對路徑的寫法雖然比較麻煩，但是絕對不會有問題。 如果使用相對路徑在程式當中，則可能由於你執行的工作環境不同，導致一些問題的發生。
因此，**在進行工作排程與shell script時，強烈建議使用絕對路徑。**

### 二、目錄與檔案相關操作 ###

- `pwd` : 顯示目前所在的目錄
  `pwd -P` : 若你處在的目錄剛好是連結(link)，則不會顯示目前目錄，而是真實的路徑
- `cd` (change directory): `cd 絕對路徑` 或是 `cd 相對路徑`
- `mkdir` (make directory): 目前自己所在的這個目錄得上一個目錄
- `.` : 目前自己所在的目錄
- `..` : 目前自己所在的這個目錄得上一個目錄


### Make it your own ###

Fonts, color schemes, layouts and stylesheets are all 100% customizable so you can turn MarkdownPad into your perfect editor.

### A robust editor for advanced Markdown users ###

MarkdownPad supports multiple Markdown processing engines, including standard Markdown, Markdown Extra (with Table support) and GitHub Flavored Markdown.

With a tabbed document interface, PDF export, a built-in image uploader, session management, spell check, auto-save, syntax highlighting and a built-in CSS management interface, there's no limit to what you can do with MarkdownPad.
