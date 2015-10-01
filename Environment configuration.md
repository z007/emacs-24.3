```
C:\Users\The current user name\Roaming\.emacs
Content

(load-file "D:/OpenSource/emacs-24.3/.emacs")

```

```
D:\OpenSource\emacs-24.3\.emacs
Conten
(setenv "HOME" "D:/OpenSource/emacs-24.3")
(setenv "PATH" "D:/OpenSource/emacs-24.3")
;;set the default file path
(setq default-directory "~/")
(custom-set-variables
 ;; custom-set-variables was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 '(ansi-color-names-vector ["#2e3436" "#a40000" "#4e9a06" "#c4a000" "#204a87" "#5c3566" 

"#729fcf" "#eeeeec"])
 '(custom-enabled-themes (quote (deeper-blue))))
(custom-set-faces
 ;; custom-set-faces was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 )
;;(add-to-list 'load-path "~/.emacs.d/evil")
;;(require 'evil)
;;(evil-mode 1)
;; The following lines are always needed. Choose your own keys.

;; org http://www.cnblogs.com/Open_Source/archive/2011/07/17/2108747.html 
(add-to-list 'auto-mode-alist '("\\.org\\'" . org-mode))
(add-hook 'org-mode-hook 'turn-on-font-lock) ; not needed when global-font-lock-mode is on
(global-set-key "\C-cl" 'org-store-link)
(global-set-key "\C-ca" 'org-agenda)
(global-set-key "\C-cb" 'org-iswitchb)
```
