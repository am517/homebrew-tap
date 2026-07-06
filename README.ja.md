| 🇺🇸 [English](README.md) | 🇯🇵 日本語 |
|-|-|

# SaiKanji Tap

**SaiKanji** 向けの [Homebrew](https://brew.sh) タップ — KanjiVGを基にした、カラフルで筆順対応のフォント。

## 提供フォント

このタップは**フォントのバリエーションごとに1つのcask**を提供します。各caskは[SaiKanji GitHub Releases](https://github.com/am517/SaiKanji/releases)から対応する`.ttf`ファイルをインストールします。

利用可能なフォントは以下で確認できます：

```bash
brew search font-saikanji
```

## インストール方法

### 1. タップを追加する

```bash
brew tap am517/tap
```

### 2. タップを信頼する（初回のみ必要）

Homebrewはサードパーティのタップをセキュリティ上の理由で未信頼として扱います。以下を実行してください：

```bash
brew trust am517/tap
```

### 3. フォントをインストールする

```bash
brew install --cask font-saikanji-regular-solid
# 他のバリエーションも同様に指定できます
brew install --cask font-saikanji-balanced-gradient-grid
```

### Brewfileでの利用例

```ruby
tap "am517/tap"

cask "font-saikanji-regular-solid"
cask "font-saikanji-balanced-gradient-grid"
# 必要なバリエーションを追加してください
```

## 詳細情報

- **プロジェクトホームページ & ライブデモ**: [saikanji.moore.is](https://saikanji.moore.is)
- **ソースコード & リリース**: [github.com/am517/SaiKanji](https://github.com/am517/SaiKanji)
- **フォントのライセンス**: [CC BY-SA 4.0](https://github.com/am517/SaiKanji/LICENSE.md)

## ドキュメント

`brew help`、`man brew`、または[公式Homebrewドキュメント](https://docs.brew.sh) を参照してください。
