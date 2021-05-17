# python-fastapi-sample

Fastapi演習サンプル

1) 仮想環境を用意します。

```script
python -m venv [仮想環境名]
```

2) 仮想環境のフォルダーにリポジトリを`clone`します。

```script
git clone https://github.com/jsn-developer/python-fastapi-sample.git
```

3) 仮想環境に入ります。

```script
[仮想環境名]\Script\activate.bat
```

4) `clone`した`python-fastapi-sample`配下の`requirements.txt`を利用して、パッケージを導入する。

```script
pip install -r python-fastapi-sample\requirements.txt
```

5) サンプルを実行する。

```script
uvicorn python-fastapi-sample.main:app --reload
```
