# DB 編集仕様

※CRUD といいつつ CUD のみ

| 処理         | 　 CRUD | 更新元データ | 取得元.項目名                   | 編集仕様       | 備考 |
| ------------ | ------- | ------------ | ------------------------------- | -------------- | ---- |
| 3.タスク登録 | C       | id           | 自動採番                        | auto_increment |
|              |         | user_id      | 2.ユーザ取得で取得した{user}.id |                |      |
|              |         | task_name    | {request}.name                  |                |      |
|              |         | start_date   | {request}.startDate             | yyyy-MM-dd     |      |
|              |         | end_date     | {request}.startDate             | yyyy-MM-dd     |      |
|              |         | priority_id  | {request}.priority_id           |                |      |
|              |         | note         | {request}.note                  |                |      |
