@startuml
ユーザー -> Webサーバー : 検索（商品名）
Webサーバー -> DBサーバー : 検索処理（商品名）
DBサーバー -> DBサーバー : 検索処理
DBサーバー -> Webサーバー : 検索結果
Webサーバー -> ユーザー : 検索結果
@enduml