# iceberg.emacs

A dark blue color theme for Emacs, providing a cool-headed perspective for your coding sessions.

This is an Emacs port of the [Iceberg](https://cocopon.github.io/iceberg.vim/) color scheme, originally created for Vim by cocopon.

## Screenshot

![Iceberg theme for Emacs](https://live.staticflickr.com/65535/51479421757_b0286c900a_b.jpg)

## Features

- Dark blue background with carefully selected colors for reduced eye strain
- Comprehensive face definitions for syntax highlighting
- Support for popular Emacs packages including:
  - company
  - ivy / counsel
  - flycheck
  - org-mode
  - markdown-mode
  - diff-hl
  - neotree
  - rainbow-delimiters
  - doom-modeline
  - and more

## Installation

### Manual Installation

1. Download `iceberg-theme.el` to a directory in your `load-path`
2. Add the following to your Emacs configuration:

```elisp
(load-theme 'iceberg t)
```

### Using use-package with local file

```elisp
(use-package iceberg-theme
  :load-path "path/to/iceberg.emacs"
  :config
  (load-theme 'iceberg t))
```

## Credits

- Original colorscheme: [cocopon](https://github.com/cocopon)
- Emacs port: [apnsngr](https://github.com/apnsngr)
- Modifications: [minorugh](https://github.com/minorugh)

## License

MIT 
