### Pogema で色々遊んでみる

```sh
# venv を使った仮想環境の作成
python3 -m venv .venv

# 仮想環境のアクティベート
source .venv/bin/activate

# pip のアップグレード
python3 -m pip install --upgrade pip

# ライブラリのインストール
pip install -r requirements.txt
```

```sh
# pip-tools のインストール
pip install pip-tools

# pip-tools による requirements.txt の作成
pip-compile requirements.in
```
