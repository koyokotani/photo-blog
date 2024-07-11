# 写真ブログ/ポートフォリオ
https://photo-blog-9315a.web.app/

## 開発

1. Dockerを立ち上げる

```bash
docker-compose up -d
```

2. ブラウザにアクセス
```
http://localhost:3000
```

### 必要なパッケージインストール
```
docker-compose exec app yarn add <package name...>
```

## デプロイ
1. アプリケーションのDockerコンテナに接続する
```
docker-compose exec app bash
```

2. ビルド
```
yarn build
```

3. Firebaseにログインする
```
firebase login
```

4. Firebaseにデプロイする
```
firebase deploy
```