# HTML に関して

## id 名と class 名の傾向

- body タグ直下は　\[div class="container"]　で囲む
- header タグには\[id="header"], footer タグには　\[id="footer"]　を付与
- main タグ内で h1~h6 を付与するブロックがあれば　\[section class="xxx"]　を用いる
- section タグ内で子要素のブロックを中央に配置するためには　\[div class="inner"]　を用いる
- main タグ内で似たコンテンツのブロックには　\[div class="content"]　を用いる

---

## header 　に関して

- navigation メニューは　 nav タグ内にリスト表示<br>
  \<nav><br>
  　　\<ul><br>
  　　　　\<li>メニュー\</li><br>
  　　　　\<li>メニュー\</li><br>
  　　\</ul><br>
  \</nav><br>

---

## footer 　に関して

- コピーライトのマークは　\[\&copy;]　を用いる

---

## 参考フォーマット

\<\!DOCTYPE html><br>
\<html lang="ja"><br>
　　\<head><br>
　　　　\<meta charset="utf-8"><br>
　　　　\<title>PHOTO BOOK</title><br>
　　　　\<meta name="description" content="テキストテキストテキスト"><br>
　　　　\<meta name="viewport" content="width=device-width, initial-scale=1"><br>
　　　　\<link rel="shortcut icon" href="img/favicon.ico"><br>
　　　　\<link rel="stylesheet" href="css/style.css"><br>
　　\</head><br>
　　\<body><br>
　　　　\<header id="header"><br>
　　　　　　\<h1 class="site-title"><br>
　　　　　　　　\<a href="index.html"><img src=\"img/logo.svg" alt="PHOTO BOOK">\</a><br>
　　　　　　\</h1><br>
　　　　\</header><br>
　　　　\<main><br>
　　　　　　\<div id="main-visual"><br>
　　　　　　　　\<img src=\"img/xxx.jpg" alt="main-visual"><br>
　　　　　　\</div><br>
　　　　　　\<section id="aaa"><br>
　　　　　　　　\<div class="inner"><br>
　　　　　　　　　　\<h2 class="section-title">タイトル\</h2><br>
　　　　　　　　\</div><br>
　　　　　　\</section><br>
　　　　　　\<section id="bbb"><br>
　　　　　　　　\<div class="inner"><br>
　　　　　　　　　　\<h2 class="section-title">タイトル\</h2><br>
　　　　　　　　　　　　\<div class="content">\</div><br>
　　　　　　　　\</div><br>
　　　　　　\</section><br>
　　　　\</main><br>
　　\</body><br>
\</html>
