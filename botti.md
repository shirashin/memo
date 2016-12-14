## obj.try(:hoge, foo)

* objがnilの場合はhogeを実行しないでnilを返却
* hogeメソッドが存在しない場合nil返却
* fooは評価される

## obj.try!(:hoge, foo)

* objがnilの場合はhogeを実行しないでnilを返却
* hogeメソッドが存在しない場合はエラー
* fooは評価される

## obj&.hoge

* objがnilの場合はhogeを実行しないでnilを返却
* hogeメソッドが存在しない場合はエラー
* fooは条件付きで評価
