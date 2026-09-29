# Несколько версий Node через fnm

brew install fnm, в ~/.zprofile: eval "$(fnm env --use-on-cd --shell zsh)". fnm install 20 && fnm install 22 && fnm default 22 — дальше нужная версия включается сама по файлу .nvmrc в папке проекта.
