# `aspell-lv` word list

This word list was dumped from installed [Arch Linux AUR package `aspell-lv`](https://aur.archlinux.org/packages/aspell-lv) via command:

```sh
aspell -d en dump master | aspell -l en expand > aspell_lv_no_conjugations.dict
```

Word conjugations were removed via Vim command:

```vim
:%s/ .*$//g
```
