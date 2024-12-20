# WXT-1stExtension

WXTで拡張機能を作る

---

# 手順

## Nodeを最新化

```sh
volta install node@latest
volta install npm@latest
```

## WXTのインストール

```sh
npx wxt@latest init 1stext
```

> ✔ Choose a template › vue
>
> ✔ Package Manager › npm

```sh
cd 1stext

# volta pin node@23.5.0
# volta pin npm@11.0.0

npm install
```

<details>
  <summary>一時的なエラーの解決策</summary>

`(define name):1:0: ERROR: Expected identifier but found "import"` と出力された場合は、以下のコマンドを実行する。

```sh
npm i -D esbuild@0.24.0
```

</details>

```sh
npm run dev
```

---

Copyright (c) 2024 YA-androidapp(https://github.com/yzkn) All rights reserved.
