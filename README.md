# sublime-fast-snippets-with-php (Sublime快速片段生成PHP對應Class與Method)

Sublime snippets is powerful function, customize some snippets to create PHP useful method and class.
Sublime片段生成是一個強大的功能，客製化相關片段設置可以快速產生PHP的method與class.


##Installation 安裝

change directory to your sublime configure local
切換到sublime的設定目錄下，各個作業系統預設路徑如下：

ubuntu:
```
    .config/sublime-text-3/Packages/User
```

mac:
```
    ~/Library/Application Support/Sublime Text 3/Packages/User
```

windows:
```
    Sublime Text 3/Packages/User
```

and you can do `git clone`:
接著你可以使用 `git clone`安裝:

```
    git clone https://github.com/Mombuyish/sublime-fast-snippets-with-php.git
```
or you can also download `.zip` and unzip, put in there.
或者你可以使用下載`.zip`並且解壓縮放在指定路徑。

##Usage 使用方法

Here is customize shortcuts in sublime.
這邊是自訂的快捷鍵。
Support `tab` to previous/next slug.
使用`tab`做上下一步的快速切換。

| shortcut  | function                             |
| --------- |--------------------------------------|
| class     | build class with namespace           |
| aclass    | build abstract class with namespace  |
| _c        | build construct method               |
| met       | build method                         |

| 快捷鍵   | 功用                                    |
| --------- |-------------------------------------- |
| class     | 建立含有namespace的class                   |
| aclass    | 建立含有namespace的抽象class             |
| _c        | 建立construct方法                         |
| met       | 建立方法（可透過tab進行修改公開保護私有）    |

And also, support Laravel 5.1~ shortcuts.
當然，也有支援Laravel 5.1的快捷鍵

###Laravel 5.1
| shortcut  | function                             |
| --------- |--------------------------------------|
| larac     | build laravel controller (plain)     |
| laram     | build laravel model                  |
| larar     | build laravel request                |
| rest      | build laravel controller on RESTful  |

| 快捷鍵  | 功用                             |
| --------- |--------------------------------------|
| larac     | 建立空白的controller     |
| laram     | 建立model                  |
| larar     | 建立request                |
| rest      | 建RESTful controller  |

##Notice 注意事項
Those shortcuts are active `.php` file, Use `<?php` to define the file type.
這些快捷鍵僅在`.php`檔案，並且開頭必須是`<?php`定義這個檔案的類型才有作用。

Enjoy it.