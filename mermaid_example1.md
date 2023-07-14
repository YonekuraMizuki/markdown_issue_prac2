## はじめに(Mermaidとは)

ダイアグラム作成およびチャート作図用のJavaScriptライブラリです。

また、フローチャート、シーケンス図、ガントチャート、円グラフなどいろいろな図表を作成できます。
作図にはマークダウン記法が利用でき、作図したものはPNG/JPEGで書き出す事もできます。

## Mermaidを利用する方法


使用開始までの手順は以下となります。

- VSCodeのインストール
  
- Markdown Preview Mermaid Supportプラグインのインストール　　
※最新ver.ならインストールの必要はなし。

- Markdown Preview Enhancedプラグインのインストール　　　　
※必須ではないですが、扱いやすくなります。

以上です。

あとは以下の様にマークダウンファイル内に記述してプレビューするだけです。

-構文-

```                             
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
-図式-

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

※引用元はこちら↓  
[VSCodeでMermaidを使ったダイアグラム作成(エンジニアルート)](https://www.engineer-route.com/column/8973/)



