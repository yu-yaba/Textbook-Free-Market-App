## 新潟大学教科書フリマアプリのバックエンドリポジトリ
### 新潟大学プログラミングサークルPLOTのチーム開発プロジェクトです

### セットアップ

#### .envファイルを作成
* 以下は例です。任意の値を設定してください
```env
DATABASE_HOST=db
DATABASE_USERNAME=postgres
DATABASE_PASSWORD=password
```

#### Dockerコンテナの起動
```
docker-compose build
```

```
docker-compose up
```

#### localhostにアクセス
```
http://localhost:3000/
```
