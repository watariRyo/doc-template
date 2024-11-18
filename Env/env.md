## マスタ系

### 環境変数

| サーバ         | 変数名                  | 型     | 秘匿 | local                 | 　 dev           | 　 stg           | 　 prod           |
| -------------- | ----------------------- | ------ | ---- | --------------------- | ---------------- | ---------------- | ----------------- |
| サーバサイド   | AUTH0_CLIENT_KEY        | string |      | LOCAL_KEY             | DEV_KEY          | STG_KEY          | PROD_KEY          |
| サーバサイド   | AUTH0_CLIENT_SECRET     | string | 〇   | LOCAL_SECRET          | DEV_SECRET       | STG_SECRET       | PROD_SECRET       |
| フロントエンド | PUBLIC_BACKEND_ENDPOINT | string |      | http://localhost:8080 | https://dev.com/ | https://stg.com/ | https://prod.com/ |

### セッション

| 論理名   | 物理名     | 型     | 更新タイミング | 取得元 | 　 備考 |
| -------- | ---------- | ------ | -------------- | ------ | ------- |
| sub      | sub        | string | ログイン時     | IdP    |         |
| 有効期限 | expired_at | string | ログイン時     | IdP    |         |
