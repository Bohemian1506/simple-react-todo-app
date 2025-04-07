# シンプルなReact Todoアプリ

このプロジェクトは、Reactで作成されたシンプルなTodoリストアプリケーションです。

## 機能

- タスクの追加
- タスクの完了/未完了の切り替え
- タスクの削除

## 使用技術

- React (Hooks: useState)
- CSS

## インストール方法

```bash
# リポジトリをクローン
git clone https://github.com/Bohemian1506/simple-react-todo-app.git

# プロジェクトディレクトリに移動
cd simple-react-todo-app

# 依存関係のインストール
npm install

# アプリケーションの起動
npm start
```

アプリケーションは http://localhost:3000 で実行されます。

## プロジェクト構造

```
simple-react-todo-app/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── TodoList.js
│   │   └── TodoItem.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
└── package.json
```

## 学習ポイント

- Reactコンポーネントの作成と構成
- React Hooksを使った状態管理（useState）
- コンポーネント間のデータとイベントの受け渡し
- CSSを使ったスタイリング

## ライセンス

MIT
