# Vue 3 + TypeScript + Vite + Vuetify 3

このテンプレートは、ViteでVue 3、Vuetify、TypeScriptを使用する開発を始めるのに役立ちます。テンプレートはVue 3の `<script setup>`SFCを使用しています。詳細は[script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup)を参照してください。

## おすすめのIDE設定

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)

## このテンプレートには何が含まれていますか

- Vue 3: 最新のVue 3機能を使用したテンプレートです。シングルファイルコンポーネントと `<script setup>` モードにより、コードがより簡潔で読みやすくなります。
  ルーター、ディレクティブ、ミドルウェア、ミックスインはすべて設定済みでテンプレートに組み込まれています。
- TypeScript: プロジェクト全体が型付き形式で書かれています。
- Vite: プロジェクトはVite上に構築されており、サーバーサイドレンダリングからプロダクションバンドルまで全てが強化されています。Viteの公式記事<https://vitejs.dev/guide/why.html>から詳細を知ることができます。
- Vuetify 3: Vuetify 3のアルファバージョンが完全に設定されており、カスタムテーマや色も含まれています。
- SCSS: Sassがグローバルに設定されており、ローカルコンポーネント内でも統合されています。また、Vuetifyとも統合されています。
- Vuex Store: ストアはモジュール形式で設定されており、中規模から大規模のプロジェクトに適した複数のバージョンを持つストアをサポートしています。

## 最新のアップデート

- マルチ言語設定(i18n)が追加されました。

## `.vue`インポートの型サポート

TypeScriptは`.vue`インポートの型情報を扱えないため、デフォルトではそれらは汎用的なVueコンポーネント型としてシム化されます。テンプレートの外でのプロパティ型が気にならない場合、これでも問題ありません。しかし、手動で`h(...)`呼び出しを行う場合など、実際のプロパティ型を取得したい場合、Volarの`.vue`型サポートプラグインを有効にすることで可能です。VSCodeコマンドパレットから`Volar: Switch TS Plugin on/off`を実行してください。
