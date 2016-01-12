# Django_form_sample

## セットアップ
```
# 任意のGit用ディレクトリへ移動
>cd path\to\dir

# GitHubからカレントディレクトリへclone
path\to\dir>git clone https://github.com/thinkAmi-sandbox/Django_form_sample.git .

# virtualenv環境の作成とactivate
path\to\dir>virtualenv -p c:\python34\python.exe env
path\to\dir>env\Scripts\activate

# requirements.txtよりインストール
(env)path\to\dir>pip install -r requirements.txt

# マイグレーションと初期データ投入
(env)path\to\dir>python manage.py migrate
(env)path\to\dir>python manage.py loaddata initial_data

# 開発サーバの起動
(env)path\to\dir>python manage.py runserver

# 開発サーバのURLを既定のブラウザで開く
# (別のコマンドプロンプトを開いて実行)
>start http://localhost:8000/site/register
```

　  
## テスト環境

- Windows10
- Python 3.4.3
- Django 1.9.1

　  
## 関係するブログ

- [Djangoで、GitHubに上げたDjangoアプリの再利用を試してみた - メモ的な思考的な](http://thinkami.hatenablog.com/entry/2016/01/11/005056)