# .DS_Store не должен попадать в git

Finder создаёт в папках служебный файл `.DS_Store`. Один раз для всех проектов: `echo .DS_Store >> ~/.gitignore_global && git config --global core.excludesfile ~/.gitignore_global`.
