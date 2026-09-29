# С Windows на Mac: кириллица в именах файлов

Буквы вроде «Й» могут распаковаться в разложенном виде (И + знак), и git покажет закоммиченные файлы как новые. git config --global core.precomposeunicode true.
