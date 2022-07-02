# discordpy project template

```bash
.
├── README.md
├── discord_bot         # projectファイル
│       ├── env.py      # 環境変数設定関係
│       └── main.py     # discordpyスクリプト
├── doc
├── poetry.lock         # poetry依存関係
└── pyproject.toml      # pythonプロジェクトにおける開発設定ファイル
```

## スクリプトの実行方法

discord.pyのテンプレートを実行する方法です。

1. __`.env`ファイルの作成__

.envファイルをプロジェクトルートに作成します。`<アクセストークン>`には、discord bot作成時のアクセストークンを設定します。

```text
BOT_TOKEN=<アクセストークン>
```

2. __スクリプトの実行__

README作成時の環境は下記の通りです。

```bash
# python --version
Python 3.10.5

# which python
/usr/local/bin/python
```

下記でbotが実行されます。

```bash
python ./discord_bot/main.py
```

成功するとbotのログインがターミナル上で通知されます。

3. __discordから確認__

botをインストールしたdiscordサーバーにて、`/neko`とコマンドを入力します。

![image](/doc/image/discordpy-template-1.png)

botから返信があれば成功です。
