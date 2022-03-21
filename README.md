# ac-tweet-bookmarklet

▼ #DAZ3D #DAZStudio が無いやつ
```
javascript:var d=document,w=window,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=(e?e():(k)?k():(x?x.createRange().text:0)),s2=((s.toString()==%27%27)?s:(enc(s)+enc("\u000d\u000a"))),f=%27https://twitter.com/intent/tweet%27,l=d.location,p=%27?text=%27+s2+enc(l)+enc("\u000d\u000a\u0023\u30a4\u30e9\u30b9\u30c8\u0041\u0043\u0020\u3088\u308a\u30d5\u30ea\u30fc\u30c0\u30a6\u30f3\u30ed\u30fc\u30c9\u000d\u000a\u000d\u000a\u000d\u000a\u000d\u000a"),u=f+p;try{if(!/^(.*.)?tumblrzzz[^.]*$/.test(l.host))throw(0);tstbklt();}catch(z){a =function(){if(!w.open(u))l.href=u;};if(/Firefox/.test(navigator.userAgent))setTimeout(a,0);else a();}void(0)
```

▼ SWORC 用 #DAZ3D #DAZStudio があるやつ。上のに普通にタグ文字列追加すればいいです。
```javascript
javascript:var d=document,w=window,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=(e?e():(k)?k():(x?x.createRange().text:0)),s2=((s.toString()==%27%27)?s:(enc(s)+enc("\u000d\u000a"))),f=%27https://twitter.com/intent/tweet%27,l=d.location,p=%27?text=%27+s2+enc(l)+enc("\u000d\u000a\u0023\u30a4\u30e9\u30b9\u30c8\u0041\u0043\u0020\u3088\u308a\u30d5\u30ea\u30fc\u30c0\u30a6\u30f3\u30ed\u30fc\u30c9\u000d\u000a\u000d\u000a\u000d\u000a\u000d\u000a\u0023\u0044\u0041\u005a\u0033\u0044\u0020\u0023\u0044\u0041\u005a\u0053\u0074\u0075\u0064\u0069\u006f"),u=f+p;try{if(!/^(.*.)?tumblrzzz[^.]*$/.test(l.host))throw(0);tstbklt();}catch(z){a =function(){if(!w.open(u))l.href=u;};if(/Firefox/.test(navigator.userAgent))setTimeout(a,0);else a();}void(0)
```

javascript:var d=document,w=window,enc=encodeURIComponent,e=w.getSelection,k=d.getSelection,x=d.selection,s=(e?e():(k)?k():(x?x.createRange().text:0)),s2=((s.toString()==%27%27)?s:(enc(s)+enc("\u000d\u000a"))),f=%27https://twitter.com/intent/tweet%27,l=d.location,p=%27?text=%27+s2+enc(l)+enc("\u000d\u000a\u0023\u30a4\u30e9\u30b9\u30c8\u0041\u0043\u0020\u3088\u308a\u30d5\u30ea\u30fc\u30c0\u30a6\u30f3\u30ed\u30fc\u30c9\u000d\u000a\u000d\u000a\u000d\u000a\u000d\u000a\u0023\u0044\u0041\u005a\u0033\u0044\u0020\u0023\u0044\u0041\u005a\u0053\u0074\u0075\u0064\u0069\u006f"),u=f+p;try{if(!/^(.*.)?tumblrzzz[^.]*$/.test(l.host))throw(0);tstbklt();}catch(z){a =function(){if(!w.open(u))l.href=u;};if(/Firefox/.test(navigator.userAgent))setTimeout(a,0);else a();}void(0)

日本語の変換は [テキスト変換サービス](https://winofsql.jp/php/cnvtext/frame.htm)

で、

![image](https://user-images.githubusercontent.com/1501327/159191596-4449e7f6-bd57-4613-87fc-fdcc8647c592.png)

長い文字列は改行とかたくさん入って以下の部分

![image](https://user-images.githubusercontent.com/1501327/159191683-ceb96d2b-53ea-44b5-b0e0-dd1576333652.png)

![image](https://user-images.githubusercontent.com/1501327/159191701-0c8a7fa9-2ce5-456f-8a9d-e85771cf2bd8.png)

## 実行手順

タイトル選択して、画像をクリップボットにコピーしておいてブックマークレットを実行する

![image](https://user-images.githubusercontent.com/1501327/159195744-f67a8b7a-9108-4fc0-9a63-e56c64ffa4bf.png)

