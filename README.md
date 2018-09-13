# HTML Part1 基本編

## 目次
- HTMLとは？
- タグとは？
- タグの種類
- head要素 body要素とは？
- 階層とは？
- 試しに作ってみよう


## HTMLとは
HTMLとはWebサイトを作るために使う言語です。Word、Excelが紙に文字、画像を配置するようにHTMLはWebに文字、画像を配置するために使われます。
HTMLはタグというものを使って作っていきます。

## タグとは
タグは＜＞を使います。
例：文字を書きたいとき
```html
<p>ここに文字を書きます。</p>
```
```html
<p>から始まり、終わりに</p>を書きます。
```
この間に入れたい文字を書いていきます。

## タグの種類
```html
<head> </head>　サイトの基本的な情報を書く
<body> </body>　本文、サイトのメイン部分
<title> </title>　タイトル名
<h1> </h1>　大見出し
<h2> </h2>　中見出し
<p> </p>　ひとつのまとまった文章、段落
<img>　画像

他にも数え切れないほどあります！
```

## head要素 body要素とは？
```html
<head> </head>
```
オプション設定みたいなもの
画面には表示されない
文字コード指定や他ファイルの読み込み等に使う

```html
<body> </body>
```
画面に表示される
サイトの内容は全てこちらに記載する

## 階層とは？まずはタグの説明

```html
<!DOCTYPE html>←HTMLのバージョンを指定
<html>←HTML書きますよ！
　　<head lang="ja">←基本設定を書きますよ！ langは言語を指定しますよ！
　　　　<meta charset="utf-8" />←文字を日本語に対応させますよ！
　　　　<title>Job庵</title>←タイトルを書きますよ！
　　</head>←基本設定はここまでですよ！
　　<body>←ここからが本文ですよ！
　　　　<p>Job庵プログラムです</p>←文字(段落)を書きますよ！
　　</body>←本文はここまでですよ！
</html>←HTMLはここまでですよ！
```

## 階層とは
```html
<!DOCTYPE html>
<html>
　　<head>
　　　　<meta charset="utf-8" /> ←<head></head>の中にあるので<head>が親になります。
　　　　<title>Job庵</title>     ←<head></head>の中にあるので<head>が親になります。
　　</head>
　　<body>
　　　　<p>Job庵プログラムです</p>
　　</body>
</html>
```

## 試しに作ってみよう①

まずはこれを書こう！

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Job庵</title>
    </head>
    <body>
        <p>Job庵プログラムです</p>
    </body>
</html>
```
次からは
```html
<body></body>
```
の間に記述していきます.

```html
    <h1>大見出し</h1>
    <p>大見出しはタイトルに使うことが多いです。</p>
    <h2>中見出し</h2>
    <p>多くの見出しはこの見出し</p>
    <h3>小見出し</h3>
    <p>中見出しの中の見出しに使います</p>
```

※補足
```html
見出し
<h1></h1>
<h2></h2>
<h3></h3>
```

## 試しに作ってみよう②
①の続きから書こう！
```html
    <h2>今夜の晩御飯</h2>
    <ul>
        <li>ハンバーグ</li>
        <li>ごはん</li>
        <li>味噌汁</li>
    </ul>
```

※補足
```html
リスト(箇条書き)
<ul>
    <li></li>
    <li></li>
    <li></li>
</ul>
```

## 試しに作ってみよう③
②の続きから書こう！
```html
<p><a href=“https://www.google.co.jp/”>Google</a></p>
<p><a href=“http://www.yahoo.co.jp/” target=“_blank”>Yahoo</a></p>
```
※補足
```html
リンク
<a href=”リンク先”></a>
```
