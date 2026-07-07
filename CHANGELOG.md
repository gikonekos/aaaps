# CHANGELOG

人間が読むための改訂履歴です。Gitのコミット履歴とは別に、「何が変わったか」を要約します。

## draft0.1
- 初版。単一ファイルの規約案（Gemini草案ベース）。

## draft0.2
- README / AAAPS-v1（本体） / GOVERNANCE / HISTORY / CREDITS / evidence に分離。
- 権利主張の範囲を「擬古猫」固有の創作物に限定（第2条）。
- 第3条を「禁止する」から「同意せず異議を表明する／立証資料として機能することを企図する」に軟化。
- 第5条のコピーレフト継承を「しなければならない（MUST）」に変更。
- 第6条でCC BY-SA 4.0を基盤ライセンスと明記。
- タカラ事件（2002年）をHISTORY.mdに追記。AAAP名称の由来（解散済NPOへの敬意）を明記。
- Facebookアイコン画像を `assets/` に格納。

## draft0.3
- 第5条を「強く推奨します（SHOULD）」に戻し、MUST/SHOULDを未確定事項として明記。
- 第6条を「CC BY-SA等を参考とする」という慎重な表現に修正し、法的関係は未確定事項として保留。
- GOVERNANCE.mdに「未確定事項」節を新設（第5条・第6条を列挙）。
- HISTORY.mdの冒頭に「良いことも悪いことも保存・公開する」という理念文を追加。
- 「立証する」という表現を「補強資料となることを企図する」「最終評価は専門家・第三者に委ねる」に修正。
- `evidence/wikimedia.md`・`evidence/facebook.md` を新設し、Wikimedia Commons／日本語版Wikipediaの公開記録（2006・2013・2015年）、およびFacebookページの非ログイン閲覧確認記録を、事実のみの年表として追加。
- 対応するスクリーンショットをISO 8601命名で `evidence/wikimedia/` `evidence/facebook/` に格納。
- 本CHANGELOG.mdを新設。

## draft0.4
- HISTORY.mdに「基本的な著作権認識」節を新設。AA・キャラクター作品を「自然発生」ではなく「特定個人の連鎖的な創作」として扱う基本方針を明記。
- 上記に伴い、ギコネコの由来（固定「ねこ」→「骨董屋」→命名した住人たち）を記載。出典（Wikipedia「擬古猫」記事）については、信頼性検証中であること、初出が基建吉自身の利用者ページ（oldid=10442031、2007年2月5日）に由来する一次的な当事者証言であることを注記。
- AAAPS-v1.mdに第7条（他者による援用・名称使用について）を新設。他コミュニティによる本仕様書の構造の参考利用は妨げないが、独占防止の趣旨を骨抜きにする改変版は「公式版」として扱わない旨を、断定（無効）ではなく定義（公式版とは何か）の形で規定。条番号の繰り下げに伴い、旧第7条（免責事項）は第8条に変更。
- 配布物のファイル命名から `.` の連続使用（例：`draft0.3.zip`）を廃止し、`draft0-4.zip` のようにハイフン区切りへ変更（iPad等で拡張子として正しく認識されない事例への対応）。

## draft0.5
- `en/README.md`・`en/AAAPS-v1.md` を新設。README.mdからの導線も追加。
- 日本語版が正本（authoritative）であり、英語版は参考訳（reference translation）である旨を英語版冒頭に明記。GOVERNANCE/HISTORY/CREDITS/CHANGELOG/evidenceは当面日本語のみとし、必要に応じて追って翻訳する方針。

## draft0.6
- `LICENSE.md` を新設。GitHubのライセンス検出に対応する入口ファイルとし、本文は「AAAPS-v1.mdが正本」である旨の案内に限定。
- GOVERNANCE.mdに「AIレビューの位置づけ」を2行で追加（複数生成AIの査読を参考としたが、最終判断は編集者が行う旨）。
- README.mdの構成表にLICENSE.mdを追加。

## v1.0
First public release.
- ChatGPTさんの最終査読を受け、軽微な追記を反映：en/README.mdに「canonical documents」を一度だけ併記、LICENSE.mdに"This file exists for repository tooling compatibility."を追記。

---
最新改訂日：2026年7月7日
