# org-ivy-search

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

- [x] Full text search over org files
- [x] Search on the fly
- [x] Fuzzy matching

# License

[LICENSE](LICENSE). Copyright (c) 2022 Huming Chen <chenhuming@gmail.com>
