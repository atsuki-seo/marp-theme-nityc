# marp-theme-nityc

弓削商船高等専門学校のMarpテーマ（非公式）

## 概要

このプロジェクトは、[Marp](https://marp.app/) で使用できる弓削商船高等専門学校向けのプレゼンテーションテーマです。

## 特徴

- **校章の自動表示**: ヘッダーに弓削商船高等専門学校の校章が自動で表示されます
- **特別なスライドクラス**: 
  - `title`: タイトルスライド用の背景画像付きデザイン
  - `end`: 終了スライド用の全画面背景画像付きデザイン
- **カスタムスタイル**:
  - `summary-positive`: 緑色の枠線で囲まれた強調表示の枠（ポジティブな内容用）
  - `summary-negative`: 赤色の枠線で囲まれた強調表示の枠（ネガティブな内容用）

## インストール方法

### VSCode Marp拡張機能を使用する場合

1. VSCodeで設定を開く (`Ctrl + ,`)
2. 「Marp: Themes」または「markdown.marp.themes」を検索
3. CSSファイルへのローカルパスまたはリモートパスを追加
  - `https://raw.githubusercontent.com/atsuki-seo/marp-theme-nityc/refs/heads/main/theme/yuge.css`
  - ※ 上記のリンクでも問題ないが、リポジトリをフォークしてGitHub Pagesなどでホストして利用することを推奨します
4. Markdownファイルの先頭でテーマを有効する：

```yaml
---
marp: true
theme: yuge
paginate: true
header: 'ヘッダーテキスト'
footer: 'フッターテキスト'
---
```

5. すぐに反映されない場合は、VSCodeを再起動してください

追加設定（`size`や`paginate`など）については、[公式ドキュメント](https://github.com/marp-team/marp/blob/main/website/docs/guide/directives.md)を参照してください。


### 3. 特別なクラスの使用

#### タイトルスライド
```markdown
<!--
class: title
-->
# プレゼンテーションタイトル
```

#### 終了スライド
```markdown
<!--
class: end
-->
# END
```

#### 強調表示の枠
```markdown
<div class="summary-positive">

✓ 成功事例や良い点を強調

</div>

<div class="summary-negative">

✗ 問題点や注意事項を強調

</div>
```

## 使用例

詳細な使用例は [`sample/sample.md`](sample/sample.md) を参照してください。

## 技術仕様

- **対応Marp**: Marp CLI, Marp for VS Code
- **外部リソース**: 
  - 校章: `https://www.yuge.ac.jp/`から取得
  - 背景画像: `https://www.facebook.com/yugeshosen`から取得
- **ベーステーマ**: Marp default theme

## ライセンス

MIT License - 詳細は [LICENSE](LICENSE) ファイルを参照してください。

## 注意事項

- このテーマは非公式であり、弓削商船高等専門学校が公式に提供するものではありません
- 校章や背景画像の著作権は弓削商船高等専門学校に帰属します

## 貢献

バグ報告や機能要求は[Issues](https://github.com/atsuki-seo/marp-theme-nityc/issues)からお気軽にお寄せください。