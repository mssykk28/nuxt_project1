# nuxt_project_1

## ビルドセットアップ

``bash

# 依存関係のインストール

$ npm install

# localhost:3000 でホットリロードして提供する。

npm run dev

# 本番用にビルドしてサーバーを立ち上げる

npm run build
npm run start

# 静的プロジェクトの生成

npm run generate

```

詳しい仕組みについては、[documentation](https://nuxtjs.org)をご覧ください。

## 特殊なディレクトリ

以下の追加ディレクトリを作成することができ、そのうちのいくつかは特別な動作をします。pages`だけが必要です。これらの機能を使用しない場合は、削除して構いません。

### `assets`

assets ディレクトリには、Stylus や Sass ファイル、画像、フォントなど、コンパイルされていないアセットが格納されます。

このディレクトリの使用方法については、[ドキュメント](https://nuxtjs.org/docs/2.x/directory-structure/assets) を参照してください。

### `components`

componentsディレクトリには、Vue.jsのコンポーネントが含まれています。コンポーネントは、ページのさまざまな部分を構成し、ページ、レイアウト、さらには他のコンポーネントに再利用したり、インポートしたりすることができます。

このディレクトリの使い方については、[the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components)で詳しく説明しています。

### `layouts`

レイアウトは、Nuxtアプリのルック＆フィールを変更したいときに、サイドバーを含めたり、モバイル用とデスクトップ用の個別のレイアウトを用意したりするのに非常に便利です。

このディレクトリの使用方法については、[the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts)で詳しく説明しています。

### `pages`

このディレクトリには、アプリケーションのビューとルートが含まれます。Nuxtはこのディレクトリ内のすべての `*.vue` ファイルを読み込み、Vue Routerを自動的にセットアップします。

このディレクトリの使い方については、[the documentation](https://nuxtjs.org/docs/2.x/get-started/routing)を参照してください。

### `plugins`

pluginsディレクトリには、ルートVue.jsアプリケーションをインスタンス化する前に実行したいJavaScriptプラグインが含まれています。ここは、Vueプラグインを追加したり、関数や定数を注入したりする場所です。Vue.use()` が必要になるたびに、 `plugins/` にファイルを作成し、そのパスを `nuxt.config.js` の plugins に追加する必要があります。

このディレクトリの使い方については、[the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins)に詳細が記載されています。

### `static`

このディレクトリには、静的ファイルが格納されます。このディレクトリ内の各ファイルは `/` にマップされます。

例: `/static/robots.txt` は `/robots.txt` にマップされます。

このディレクトリの使い方は、[ドキュメント](https://nuxtjs.org/docs/2.x/directory-structure/static)に詳しく書かれています。

### `store`

このディレクトリには、Vuexのストアファイルが格納されます。このディレクトリにファイルを作成すると、自動的にVuexが有効になります。

このディレクトリの使用方法については、[ドキュメント](https://nuxtjs.org/docs/2.x/directory-structure/store)で詳しく説明しています。

アイコンの参考URL
https://pictogrammers.github.io/@mdi/font/2.0.46/
```
