(package "company-kaomoji"
         "0.1.0"
         "Company backend for Kaomoj")

(website-url "https://github.com/jcs-elpa/company-kaomoji")
(keywords "matching" "kaomoji")

(package-file "company-kaomoji.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source "gnu")
(source "melpa")
(source "jcs-elpa")

(source-priority "gnu"      0)
(source-priority "melpa"    5)
(source-priority "jcs-elpa" 10)

(depends-on "emacs" "26.1")
(depends-on "company")
(depends-on "kaomoji")
(depends-on "ht")

(development
 (depends-on "ert-runner"))

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432
