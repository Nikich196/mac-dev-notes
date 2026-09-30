# SSH-ключ для GitHub

`ssh-keygen -t ed25519 -C "почта"` — создать ключ. `pbcopy < ~/.ssh/id_ed25519.pub` — скопировать открытую часть и добавить её в GitHub: Settings → SSH and GPG keys. Проверка: `ssh -T git@github.com`.
