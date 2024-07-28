# README
# users

| Column | Type       | Options                   |
| ------ | ---------- | --------------------------|
| email  | string     | null: false, unique: true |
| encrypted_password  | string | null: false      |
| name                | string | null: false      |
| profile | text | null: false |
| occupation | text | null: false |
| position | text | null: false |



# prototype

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| title | string | null: false |
| catch_copy | text | null: false |
| concept | text | null: false |
| user | text | foreign_key: true, null: false |

# comments

| Column | Type       | Options                        |
| ------ | ---------- | ------------------------------ |
| content | text | null: false |
| prototype | references | null: false, null: false |
| user | references | null: false, null: false |