# Mackerel

---

# 公式

- [Mackerel（マカレル）: 新世代のサーバ管理・監視ツール](https://mackerel.io/ja/)

# 導入・設定

- [エージェントをインストールする \- Mackerel ヘルプ](https://mackerel.io/ja/docs/entry/howto/install-agent)
- [チェック監視に公式チェックプラグイン集を使う \- Mackerel ヘルプ](https://mackerel.io/ja/docs/entry/howto/mackerel-check-plugins)
- [プロセス監視をおこなう \- Mackerel ヘルプ](https://mackerel.io/ja/docs/entry/howto/check/process)
- [ログ監視をおこなう \- Mackerel ヘルプ](https://mackerel.io/ja/docs/entry/howto/check/log)

---

# コマンド

## 起動・停止

```
$ sudo service mackerel-agent start
$ sudo service mackerel-agent stop
$ sudo service mackerel-agent restart
$ sudo service mackerel-agent reload
```

## コンフィグチェック

```
$ mackerel-agent configtest
```

## 動作確認

```
$ sudo journalctl -u mackerel-agent.service
```

## 設定ファイル編集

```
$ sudo vi /etc/mackerel-agent/mackerel-agent.conf
```
