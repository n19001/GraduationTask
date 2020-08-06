# GraduationTask

# クラウドでの出欠、入退出管理
***物理的なセキュリティではなく、出欠確認と催促メール***
<br />  
<br /> 

# クラウドで管理するもの
* データベース  
* http(Apache)  
* Appサーバー  
<br /> 
 
### メモ 
クラウドで顧客のIDとPSを保管している

# データベースで管理するもの
> 改善前のDB構造
>> 　各教室のID、PW  
>> 　教室に登録されている生徒（ユーザー）のデータ

<br />

## 仕様書？  
入退出を取る時は教室などの入口に管理者用端末があり、それで入退出管理しているので管理者アカウントにユーザーの入退出、出欠の編集ができる権限を与える  
webから欠席の申請だけ許可する。（ずるな出席を防ぐため）  
出欠の確認が取れていない人にテンプレメールを送付する。（出欠の催促メール）  
出席している人の入退出を取り、欠席の人は入退出をnoneにする  

<br />

## 予定表



| | 8 | 9 | 10 | 11 | 12 | 1 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 勉強期間 | ● | ● |  |  |  |  |
| 設計の見直し |  | ● |  |  |  |  |
| DB |  | 〇 | ● |  |  |  |
| App |  | 〇 | ● |  |  |  |
| 構築 |  |  |  | 〇 |  |  |
| テスト |  |  |  | 〇 | 〇 |  |
| 追加機能 |  |  |  | ● |  |  |
|  |  |  |  |  |  |  |





<br />
