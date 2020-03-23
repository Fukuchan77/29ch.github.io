# What is NuxtJS? / NuxtJS とは

> Nuxtは、モダンな web アプリケーションを作成する Vue.js に基づいたプログレッシブフレームワークです。Vue.js 公式ライブラリ（vue、vue-router や vuex）および強力な開発ツール（webpack、Babel や PostCSS）に基づいています。 Nuxt の目標は、優れた開発者エクスペリエンスを念頭に置き、Web 開発を強力かつ高性能にすることです。

--------

## Using create-nuxt-app / プロジェクトの作成
```
npx create-nuxt-app <project-name>
```
```
yarn create nuxt-app <project-name>
```

### アプリケーションの起動
```
npm run dev
```
```
yarn run dev
```
http://localhost:3000/

--------

## Installation

### homebrewでnode.jsのインストール
```
brew install node
```

## Upgrading

1. release notes / [リリースノート](https://ja.nuxtjs.org/guide/release-notes)を確認

2. package.json ファイルの nuxt パッケージに指定されたバージョンを更新

#### Yarn
3. yarn.lock ファイルを削除します
4. node_modules ディレクトリを削除します
5. yarn コマンドを実行します
6. インストールが完了し、テストを実行した後は、他の依存関係のアップグレードも検討してください。yarn outdated コマンドが使用できます。

#### NPM
3. package-lock.json ファイルを削除します
4. node_modules ディレクトリを削除します
5. npm install コマンドを実行します
6. インストールが完了し、テストを実行した後は、他の依存関係のアップグレードも検討してください。npm outdated コマンドが使用できます。



