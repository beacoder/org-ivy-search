# org-ivy-search

Full text search for org files powered by ivy.

# Summary
This package provides a function `org-ivy-search-view' which utilizes ivy to
do a full text search over org files.

# Usage

```lisp
    (setq org-agenda-files '("~/workspace/org/"))
    (global-set-key (kbd "C-c o") #'org-ivy-search-view)
```

# Features

- [x] Full text search for org files.
- [x] Search on the fly.

# License

[LICENSE](LICENSE). Copyright (c) 2022 Huming Chen <chenhuming@gmail.com>
