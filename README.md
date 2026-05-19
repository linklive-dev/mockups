# mockups

ナレカン プロダクトのUI/UXモックアップ集です。

## モックアップ一覧

| モックアップ | プラットフォーム | 説明 | URL |
|---|---|---|---|
| [AI検索 フリーテキスト追加質問](./ai-search-freeform/) | Web | HIT時：追加質問チップ + 参照元リンク（ファイル/記事アイコン区別） | [🔗 デモ](https://linklive-dev.github.io/mockups/ai-search-freeform/) |
| [AI検索 C案：言い換え＋知恵袋連携](./ai-search-plan-c/) | Web | MISS→言い換えサジェスト＋知恵袋誘導→HIT の体験フロー | [🔗 デモ](https://linklive-dev.github.io/mockups/ai-search-plan-c/) |
| [AI検索 フリーテキスト（モバイル）](./ai-search-freeform-mobile/) | Mobile | HIT時のモバイル版。narekan-mobile のデザインシステム準拠 | [🔗 デモ](https://linklive-dev.github.io/mockups/ai-search-freeform-mobile/) |
| [AI検索 C案（モバイル）](./ai-search-plan-c-mobile/) | Mobile | MISS時のモバイル版。縦並びチップ＋知恵袋ボタン | [🔗 デモ](https://linklive-dev.github.io/mockups/ai-search-plan-c-mobile/) |

## 使い方

各デモURLをブラウザで開くと、インタラクティブに操作できます。

### Web版 共通操作
- ページ読み込み後、初回質問が自動入力されます
- 送信ボタン（↑）を押すと、AIが回答をストリーミング表示します
- 回答後に表示される **おすすめ質問チップ** をクリックすると、追加質問が自動送信されます
- 最大5ターンの会話ラリーが可能です
- 5ターン到達後は「新しい話題で検索」で会話をリセットできます

### モバイル版 デザイン仕様
- **Primary Color**: `#00838f`（Web版 `#4aabb8` より濃い、narekan-mobile 準拠）
- **レイアウト**: フルスクリーン（モーダルではなく画面遷移）
- **ナビゲーション**: ← 戻るボタン + 「AI検索」タイトル
- **サジェストチップ**: 縦並び（横幅制約のため）
- **参照元アイコン**: 📎ファイル（青背景）/ 📝記事（緑背景）
- **SafeArea**: 下部にシアン色のセーフエリア配置
