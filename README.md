#5374Officialサイト[![Build Status](https://travis-ci.org/50river/5374site.svg?branch=master)](https://travis-ci.org/50river/5374site)
全国の5374を一覧できる、5374ポータルサイトを構築しています。

##ローンチした地域を追加したい方
source/5374_cities.csvに追加したい地域の情報を入力してください。  
地域コードについては、[こちら](http://www.soumu.go.jp/denshijiti/code.html)でご確認ください。


##仕様
現状多言語化、共同作業の利便性、メンテナンスの簡便性を維持するために静的サイトジェネレーターのmiddlemanを使用し開発しています。
masterブランチで開発を行いジェネレートしたファイルをgh−pagesでアウトプットしている為、編集は、masterブランチのsourceファイル,localesファイルへお願いします。


##簡単な構築手順 (Mac OS X用)

###middlemanインストールコマンド

```bash
gem install middleman
```

###必要なパッケージをインストールするコマンド

ビルドする前に実行します。

```bash
bundle install
```
結構なパッケージが入るはずです。


###パッケージのビルドするコマンド

```bash
bundle exec middleman build
```

###サーバーとして実行するコマンド
```bash
bundle exec middleman server
```

middlemanのさらに使い方に関しては、[オフィシャルページ](https://middlemanapp.com/jp/)をご覧ください。


##全国地方公共団体コード
こちらのExcelファイルなどからお探しください
http://www.soumu.go.jp/denshijiti/code.html
