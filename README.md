### Pogema で色々遊んでみる

```sh
# venv を使った仮想環境の作成
python3 -m venv .venv

# 仮想環境のアクティベート
source .venv/bin/activate

# pip のアップグレード
python3 -m pip install --upgrade pip

# ライブラリのインストール
pip install -r jupyter/requirements.txt
```

```sh
# jupyter lab の起動
jupyter lab
```

```sh
# pip-tools のインストール
pip install pip-tools

# pip-tools による requirements.txt の作成
pip-compile jupyter/requirements.in

- requirements.txt の pandas==1.3.5 に修正
```

```sh
# Docker-Compose の実行
docker-compose up -d

# jupyter の立ち上げ
http://127.0.0.1:8888

- docker のログ中に記載の token を入力
[I 2023-xx-xx xx:xx:xx.xxx ServerApp] http://xxxxxxxxxx:8888/lab?token=<この部分が token >
```

- [POGEMA 公式 GitHub](https://github.com/AIRI-Institute/pogema)
- [jupyter Docker](https://github.com/k8shiro/my-jupyter-notebook)
