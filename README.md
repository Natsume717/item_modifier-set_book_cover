# item_modifier-set_book_cover
item_modifierの1項目であるset_book_coverのサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
記入済みの本に対して、本の著者やタイトル、状態を指示したものへと変更します。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

付与された記入済みの本に対して、以下のコマンドを実行することで著者、タイトル、状態を変更することが可能です。

```copy
/item modify entity @s weapon.mainhand sample:set_book_cover
```

また、末尾のファイル指定をsample:set_book_cover_1、sample:set_book_cover_2、sample:set_book_cover_3のいずれかに変更することで、状態の指示が異なるものを適用できます。
