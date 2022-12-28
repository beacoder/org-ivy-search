# org-ivy-search

[![MIT licensed](https://img.shields.io/badge/license-GPLv3-blue.svg)](COPYING.md)
[![MELPA](https://melpa.org/packages/org-ivy-search-badge.svg)](https://melpa.org/#/org-ivy-search)
[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

Poor man's full-text search engine over org files powered by ivy.

# Summary
This package provides a function `org-ivy-search-view' which utilizes ivy to
do a full text search over org files.

# Configuration

```lisp
    (require 'org-ivy-search)
    (setq org-agenda-files '("~/workspace/org/"))
    (global-set-key (kbd "C-c o") #'org-ivy-search-view)
```

# Features

- [x] Full text search
- [x] Search on the fly
- [x] Fuzzy matching

# License

[LICENSE](LICENSE). Copyright (c) 2022 Huming Chen <chenhuming@gmail.com>
