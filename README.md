# テーブル設計

## userテーブル

| Column     | Type   | Options     |
| ---------- | ------ | ----------- |
| email      | string | null: false |
| password   | string | null: false |
| name       | string | null: false |


## plansテーブル

| Column     | Type       | Options     |
| ---------- | ---------- | ----------- |
| title      | string     | null: false |
| contents   | text       | null: false |　内容
| category_id| integer    | null: false | 予定の種類

- belongs_to :user
