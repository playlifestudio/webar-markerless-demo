# 起動方法

```
 python3 -m http.server 8080
```

iPhone などで開く場合には、Ngrok などを利用してください。

# フォルダ・ファイルについて

- `/{ウイルス名}/index.html`
  - 実際にモデルを表示している HTML ファイルです。
  - [model-viewer](https://github.com/google/model-viewer)というライブラリを用いています。
  - iOS 向けには USDZ データが必要となり、`model-viewer`タグの`ios-src`属性にファイルのパスを記述する必要があります。
  - GLB データがあれば、Blender で変換できます。