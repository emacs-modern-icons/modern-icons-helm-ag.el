<div align="center">

# modern-icons-helm-ag.el

Modern icons for Emacs [helm-ag](https://github.com/emacsattic/helm-ag).

</div>

This library integrates [modern-icons.el](https://github.com/emacs-modern-icons/modern-icons.el) to display modern and pretty SVG icons for [helm-ag](https://github.com/emacsattic/helm-ag) search results in Emacs.

## Installation

Manually include [modern-icons-helm-ag.el](modern-icons-helm-ag.el) into your Emacs load path, or using [straight.el](https://github.com/radian-software/straight.el) like below:

```elisp
(use-package modern-icons
  :straight (modern-icons :type git :host github
                          :repo "emacs-modern-icons/modern-icons-helm-ag.el"))
```

## Usage

Include the following code into your configuration file:

```elisp
(require 'modern-icons-helm-ag)
(modern-icons-helm-ag-enable)
```
