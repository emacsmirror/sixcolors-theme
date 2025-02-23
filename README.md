# SixColors Theme: an Emacs theme for nostalgic Apple users

This is my personal Emacs theme that is based on the original six colors of the old Apple logo.
If you like it, don't forget to check out also [SixColors-mode](https://github.com/mastro35/sixcolors-mode).

## Installation

I'm trying to publish the theme on Melpa so to be easily installed. 
However, to install it manually you can use straight and put in your init.el this piece of elisp:

```elisp
(straight-use-package 
 '(SixColors-theme :type git :host github :repo "mastro35/SixColors-theme" :branch "main"))

(load-theme 'SixColors t)
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## LICENSE

This theme is licensed under the GPL-3.0 license. See the LICENSE file for details.
