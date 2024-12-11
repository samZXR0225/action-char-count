# action-char-count

ビルド時こんなエラーが発生
NODEJSとOPENSSL起因
https://qiita.com/akitkat/items/f455bbc088a408cbc3a5
https://qiita.com/riversun/items/d45b26f4a7aad6e51b69

↑解決すると以下エラー
パースエラーだがLOADERが対応していない？
「Error: Module parse failed: Unexpected character '#' (13:2)」

You may need an additional loader to handle the result of these loaders.


https://sublimer.hatenablog.com/entry/2020/06/30/211330
https://qiita.com/engabesi/items/624272a8c1e35699415c
https://qiita.com/hanlio/items/2f3815ff9a73e5ba2114
https://panda-program.com/posts/nextjs-storybook-typescript-errors

対応が面倒なのでNCC自体を変更
"@zeit/ncc": "^0.22.3"
　　　　↓
"@vercel/ncc": "^0.38.3"
