## ログ

| ログ ID | ログ                  | エラーレベル | 備考 | 閾値検知        |
| ------- | --------------------- | ------------ | ---- | --------------- |
| 1       | VALIDATION_ERROR      | INFO         |      |                 |
| 2       | LOGIN_ERROR           | INFO         |      |                 |
| 3       | INVALID_DATA          | ERROR        |      | 1 分で 10 回    |
| 4       | INTERNAL_SERVER_ERROR | ERROR        |      | 1 分で 1 回以上 |
