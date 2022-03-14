# README

## usersテーブル
|Column  |Type  |Options    |
|--------|------|-----------|
|email   |string|null: false|
|nickname|string||

### Association
- has_many :posts


## postsテーブル
|Column |Type|Options|
|-------|----|-------|
|title  |text||
|content|text||

### Association
- belongs_to :user

<!-- 合計 テーブル:2
                users
                posts

-->