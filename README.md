# stlite-demo-bigquery-api

- 目的: StreamlitのUIでGoogle BigQueryの管理
- 機能: クエリ発行とデータ管理

デモ用に作っているので、機能順次増えたり変更したりしています。


## セットアップ

### 必須条件

- Python 3.11 (3.8以上で動作するはず)
- Streamlit 1.31以上
- stlite/desktop 0.51.3以上
- npm or yarn (node v18以降)

### 仮想環境

venvを用いてインストールを行います。
venvは、Pythonの標準ライブラリです。

https://docs.python.org/ja/3/tutorial/venv.html


```sh
% cd stlite-demo-bigquery-api
% python3 -m venv venv
% source venv/bin/activate
```

### インストール

ローカル開発用

```sh
(venv) % pip install -r requirements-dev.txt
```


## 起動方法

```
(venv) % streamlit run stlite_demo_bigquery/streamlit_app.py
```

## 表示確認

起動すると、デフォルトブラウザが立ち上がり表示確認ができる。

もし、ブラウザが立ち上がらない場合は、コンソールに表示されるポート付URLをブラウザで呼び出す。


## stliteで起動

```sh
% nvm use v20
% npm install
```

```sh
% npm run dump stlite_demo_bigquery -- -r requirements-stlite.txt
% npm run serve
```


# LICENCE

This package is under MIT License.
Please see [LICENSE](LICENSE) file.
