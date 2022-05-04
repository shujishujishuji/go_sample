# go_sample

###　テーブル作成SQL

```
create table "md_data" (
	"id"integer primary key autoincrement,
	"title"text not null,
	"url"text not null,
	"markdown"text
);
```