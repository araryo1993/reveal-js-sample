# reveal.js 使い方
以下について説明
- 環境準備
- スライド表示
- スライド作成
- マークダウンでの記載


# 環境準備
以下の環境を準備する
- Git (<https://git-scm.com/downloads>)
- Node.js (<https://nodejs.org/ja/>)

以下のリポジトリをclone  
```
git clone https://github.com/hakimel/reveal.js
```

# スライド表示
cloneしたリポジトリ配下で以下を実行しサーバーを起動し、スライドがブラウザにて表示される
```
npm install
npm start
```

# スライド作成
index.htmlを編集することでスライドの編集、作成が可能

# マークダウンでの記載
index.htmlのbodyに以下を記載  

```
<div class="reveal">
	<div class="slides">
		<section data-markdown="./slide.md"
			data-separator="---$"
			data-separator-vertical=">>>$">
		</section>
	</div>
</div>
```

`section data-markdown`に`.md`ファイルのパスを記載  
`data-separator`に右ページ遷移の文字を定義  
`data-separator-vertical`に下ページ遷移の文字を定義
