```
C:\Users\The current user name\Roaming\.emacs 

(load-file "D:/emacs/.emacs")

```

```
D:\emacs\.emacs

(setenv "HOME" "D:/emacs")
(setenv "PATH" "D:/emacs")

;;set the default file path c-x c-f find  filed
(setq command-line-default-directory "c:/" )

;;------------------下面可选------------vim 模式org----------------------------------------------------------------------
;;-----------------------------------插件直接下载 在配置也可-------------------------------------------------------------
;;http://emacswiki.org/emacs/Evil#toc1  
;; org 等等一系列包
;;  M-x list-packages
;;  C-s evil
;;Moving cursor over package name.
;;	i
;;	x
;;	i - mark for installation, x - to execute
;; org 包同样安装

(require 'package)
(push '("marmalade" . "http://marmalade-repo.org/packages/")
	     package-archives )
(push '("melpa" . "http://melpa.milkbox.net/packages/")
    	 package-archives)

(package-initialize)


;  Enable evil
;(add-to-list 'load-path "~/.emacs.d/elpa/evil-20151101.1655")
;(require 'evil)
;(evil-mode 1)

;; org http://www.cnblogs.com/Open_Source/archive/2011/07/17/2108747.html 
;; http://orgmode.org/

```
