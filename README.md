## Linux Command ##

在**MatLab**我們有**help**和**lookfor**，**Linux**也有類似的指令，有以下三種方式: 
- `man 指令`
- `info 指令`
- `指令 --help`

- 忘記指令: 善用Tab鍵

### 一、絕對路徑和相對路徑 ###

- 絕對路徑: 只要是由根目錄`/`寫起，就是絕對路徑的表示法
- 相對路徑: 不是由根目錄`/`寫起，就是相對路徑的表示法

- `.` : 目前自己所在的目錄
- `..` : 目前自己所在的這個目錄的上一個目錄
- `~` : 自己的家目錄


**注意**:

絕對路徑的寫法雖然比較麻煩，但是絕對不會有問題。 如果使用相對路徑在程式當中，則可能由於你執行的工作環境不同，導致一些問題的發生。
因此，**在進行工作排程與shell script時，強烈建議使用絕對路徑。**

### 二、目錄與檔案相關操作 ###

**目錄**
- `pwd` : 顯示目前所在的目錄
  - `pwd -P` : 若你處在的目錄剛好是連結(link)，則不會顯示目前目錄，而是真實的路徑
- `cd` (change directory): `cd 絕對路徑` 或是 `cd 相對路徑`
  - `cd ..` : 回到上一頁的感覺XD
- `mkdir` (make directory): 在Windows，就有點像是建立新資料夾 `mkdir 目錄名稱`
**檔案**
- `cp` (copy): `cp 來源檔案名稱 目標檔案名稱`
  - `cp 來源檔案名稱 .` : 目標檔案名稱跟來源檔案名稱一樣
  - `cp -a` : 連同權限一起複製 (a: all)
  - `cp -i` : 若目標檔案已經存在，複製前會先詢問是否取代目前的目標檔案
  - `cp -r` : 遞回(recursion)複製，連同子目錄一起複製
- `mv` (move or 變更檔名): `mv 來源檔案名稱 目標檔案名稱`
  - `cp -a` : 連同權限一起複製 (a: all)
  - `cp -i` : 若目標檔案已經存在，複製前會先詢問是否取代目前的目標檔案
  - `cp -r` : 遞回(recursion)複製，連同子目錄一起複製












