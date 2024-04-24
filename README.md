# react-monitoring-demo

## summary

react project から sentry にログ送信するデモ

## prepare

1. SENTRY_DSN を調べる

2. .env を作成する

```
touch .env
```

3. 【手順１】で調べた sentry dsn を .env の以下に設定

```
REACT_APP_SENTRY_DSN=XXXXXX

```

4. アプリを起動

```
yarn start
```
