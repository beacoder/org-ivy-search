# org-searcher

full text search for org files.

# Summary
This package provides a function `org-searcher-search-view' which utilizes ivy to
do a full text search over org files.

# Usage

```lisp
    (setq org-agenda-files '("~/workspace/org/"))
    (global-set-key (kbd "C-c o") #'org-searcher-search-view)
```

# Features

- [x] Full text search for org files.
- [x] Incremental search.

# License

[LICENSE](LICENSE). Copyright (c) 2022 Huming Chen <chenhuming@gmail.com>
