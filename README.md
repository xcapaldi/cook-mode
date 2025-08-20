# cook-mode

Basic syntax highlight of cooklang on Emacs

<p align="center"><img src="example.png" width="80%" title="example of syntax highlight" /></a></p>
<p align="center">Example of syntax highlight</p>

## Installation 
### For vanilla emacs users

If you're running Emacs 30 or newer, you can install and load cook-mode with `use-package`:

``` emacs-lisp
(use-package cook-mode
  :vc (:url "https://github.com/cooklang/cook-mode"
       :rev :newest
       :branch "master"))
```

If you're running an older version of Emacs, download the `cook-mode.el` file and add the following to your .emacs.el or .emacs.d/init.el
``` emacs-lisp
(load "/path/to/install/directory/cook-mode.el")
```

### For doom emacs user
Add the following to your packages.el 
``` emacs-lisp
(package! cook-mode
  :recipe (:host github 
            :repo "cooklang/cook-mode"))
```



