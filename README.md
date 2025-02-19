# EnvFreePT-Windows
摆脱依赖环境的网络渗透工具（Windows版）

## Dirsearch

仓库：https://github.com/maurosoria/dirsearch

打包命令：

```shell
pyinstaller \
    --onefile \
    dirsearch.py \
    --add-data "lib;lib" \
    --add-data "requirements.txt:." \
    --add-data "db:db" \
    --hidden-import=optparse \
    --hidden-import=requests \
    --hidden-import=requests_ntlm \
    --hidden-import=defusedxml \
    --hidden-import=difflib \
    --hidden-import=bs4 \
    --hidden-import=jinja2 \
    --hidden-import=sqlite3 \
    --hidden-import=colorama \
    --hidden-import=pyparsing
```

## Fscan

仓库：https://github.com/shadow1ng/fscan
