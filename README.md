# TrialClaude - ToDoアプリ

Claude Code を使って作成した、シンプルな ToDoリストアプリです。

## 概要

タスクの追加・完了・削除ができる軽量な Web アプリです。HTML / CSS / JavaScript のみで構成されており、サーバー不要で動作します。

## 機能

- タスクの追加（入力後に「追加」ボタン or Enterキー）
- チェックボックスで完了状態を切り替え
- 削除ボタン（✕）でタスクを削除

## デモ

GitHub Pages でホスティングされています。

[https://yas-2317.github.io/TrialClaude/](https://yas-2317.github.io/TrialClaude/)

## 技術スタック

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Actions（GitHub Pages への自動デプロイ）

## 開発中パッチ（Patch Notes）

### v1.1.0（開発中）

#### 追加予定の機能
- [ ] タスクの優先度設定（高・中・低）
- [ ] タスクの期限日設定
- [ ] フィルター機能（全件 / 未完了 / 完了済み）
- [ ] ローカルストレージへの保存（ページ再読み込み後もデータを保持）

#### 改善予定
- [ ] スマートフォン対応（レスポンシブデザイン強化）
- [ ] ダークモード対応
- [ ] タスクのドラッグ＆ドロップによる並び替え

---

### v1.0.0（2026-02-21 リリース）

#### 初期リリース
- タスクの追加（入力後に「追加」ボタン or Enter キー）
- チェックボックスで完了状態を切り替え
- 削除ボタン（✕）でタスクを削除
- GitHub Pages によるホスティング

---

## インストール手順

### 前提条件

- Git がインストールされていること
- モダンブラウザ（Chrome / Firefox / Edge / Safari）

### 手順

**1. リポジトリをクローン**

```bash
git clone https://github.com/yas-2317/TrialClaude.git
```

**2. ディレクトリに移動**

```bash
cd TrialClaude
```

**3. ブラウザで開く**

```bash
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

> サーバー不要・依存パッケージなしで動作します。

## ローカルでの実行方法

`index.html` をブラウザで開くだけで動作します。

```bash
# リポジトリをクローン
git clone https://github.com/yas-2317/TrialClaude.git

# index.html をブラウザで開く
open index.html   # macOS
start index.html  # Windows
```
