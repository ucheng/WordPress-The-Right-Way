# Getting Started

## 基礎 PHP

本書假設您已經擁有基本的 PHP 知識，包含了:

* [函式](http://www.php.net/manual/en/language.functions.php)
* [陣列](http://www.php.net/manual/en/language.types.array.php)
* [變數](http://www.php.net/manual/en/language.variables.php)
* [迴圈與條件式](http://www.php.net/manual/en/language.control-structures.php)
* [類別與物件](http://www.php.net/manual/en/language.oop5.php)
* [類別繼承](http://www.php.net/manual/en/language.oop5.inheritance.php)
* [多型](http://code.tutsplus.com/tutorials/understanding-and-applying-polymorphism-in-php--net-14362)
* [POST](http://www.php.net/manual/en/reserved.variables.post.php) 與 [GET](http://www.php.net/manual/en/reserved.variables.get.php)
* [變數範圍](http://www.php.net/manual/en/language.variables.scope.php)

若你並不熟悉以上概念，請確認你在繼續之前有良好的認識。

It's also assumed you have a code editor that has PHP syntax highlighting, although these will be beneficial:

* Auto Indenting
* Auto-completion
* Brace matching
* Syntax checking

## 本機端開發環境

建立本機端開發環境是一件很重要的事情。從前那些直接在線上主機修改PHP檔案並祈禱一切順利的日子已經是過去式了。

在本機端開發可提升你的工作效率, 不用再上傳和下載檔案， 並祈求擁有一個良好的網路環境, 或是等待頁面載入。在本機端開發，你可以在沒有WIFI或是手機訊號的火車上工作，並且在部署到你的正式主機前先進行測試。

這裡有幾個選項可以建置一個本機端開發環境。大致上可以分為兩類：

* 虛擬機
* 實體機

第一類通常會包含了類似 Vagrant 這類的專案，並且提供你一個標準且一致的虛擬機器來工作。

第二類則是直接安裝主機相關軟體在你的作業系統上。目前市面上有很多工具來簡化這項工作，但你的開發環境將會是獨特且比較難進行除錯的。這些工具通常稱為 LAMP, 代表著 Linux Apache MySQL PHP。

### IIS

Microsoft Internet Information Services 是一套伺服器軟體，主要用在 Windows 環境的主機上。 Variants of it come with Windows if you install the appropriate component, 但是關於如何設定 IIS 的知識在 WordPress 社群是很稀少的。大多數主機都是執行 Apache 或是 Nginx，同時開發者的知識累積也大多是朝此方向。

IIS 並不是一個容易的處理的選項。

## 版本管理

A vital part of working in teams and contributing is version control. Version control systems track changes over time and allow developers to collaborate and undo changes.

### Git

Created by Linus Torvalds the creator of Linux, [Git is a popular decentralised system](http://git-scm.com/), if you've ever been on GitHub, you've encountered git.

### Subversion

Also known as svn, this is a centralised version control system, used for the plugin and theme repositories on WordPress.org

