# README

# userテーブル

| Column   | Type   | Options     |
| -------- | ------ | ----------- |
| email    | string | null: false |
| password | string | null: false |
| name     | string | null: false |

# userテーブル

| Column    | Type         | Options                        |
| --------- | ------------ | ------------------------------ |
| title     | string       | null: false                    |
| catch_copy| text         | null: false                    |
| user      | references   | null: false, foreign_key: true |


