# ConstructionRedmineServer

Dockerを利用した Redmineサーバ構築スクリプトになります。
最短で2分程度でRedmineサーバが構築できます。
（※pullが遅い場合は、スクリプト内のコメントアウトしているdocker buildのほうをお使いください。15分程度かかります。）

## 1.構成

Redmine 3.2.0
MySQL   5.5.46

## 2.前提

Dockerが動く環境を準備します。
Windowsであれば、Docker Toolboxで構いません。
もしくは、Vagrant等で Docker Host なゲストOSを立てたうえで、構築します。

## 3.構築手順

```
 curl -fsSL https://github.com/hidetarou2013/ConstructionRedmineServer/create_start_redmine.sh| sh
```


もしくは、sudo dockerの場合のスクリプトも一応添付します。

```
 curl -fsSL https://github.com/hidetarou2013/ConstructionRedmineServer/sudo_create_start_redmine.sh| sh
```

##4. Redmine URL

http://<Docker Host IP Address>:10080/

admin/admin



