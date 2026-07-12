# CHANGELOG

人間が読むための改訂履歴です。Gitのコミット履歴とは別に、「何が変わったか」を要約します。

## v1.1（2026年7月12日）
- Grokさんによるリポジトリ精査を受け、AAAPS-v1.md第6条にCreative Commons BY-SA 4.0・GFDLの公式ページへのリンクを追加。権利義務の内容に変更はないが、規範本体（AAAPS-v1.md）への変更のためマイナーバージョンとして扱う。
- en/AAAPS-v1.mdにも同様のリンクを追加。
- Grokさんの別提案（GOVERNANCE.mdへのFacebookグループURL明記）は却下。

## v1.0.2（2026年7月12日）
- `evidence/kindle-2020.md` を新設。2020年公表のKindle本「あやしいわーるど＠暫定【過去ログ】2002年08月29日」の奥付に「#AAAP Licensed」の表記があることを記録。GitHub公開（2026年）より6年前から同表記が継続利用されていたことを示す資料。
- 表紙制作に用いられたコミPo!（パッケージ版、2015年購入）について、製品版の商用利用が規約上問題ないことを確認し付記。
- `evidence/qptn-fc2.md` を新設。2013年、活動サイトqptn.x.fc2.comの投稿内に、アスキーアートとして「#AAAP」の文字列が埋め込まれていたことを記録。同サイトのハンドル名「qptn」が2026年のX告知アカウント@qptnと同一であることも付記。原文（テキスト）を正確に転記。
- 上記原文について、当初「Born at October 11,2012」と転記していたが、秀丸での確認により一時「2022」の誤りと判断し訂正した。しかしその後、PCブラウザでの実際の表示を再確認した結果、原文は「2012」で正しく、秀丸ファイル側に問題があったことが判明したため、「2012」に再訂正。秀丸スクリーンショットは信頼性に疑義があるため破棄し、PCブラウザでの表示スクリーンショットに差し替えた。一連の訂正の経緯を含めて記録。
- `evidence/README.md` に両ファイルへの参照を追加。

## v1.0.1（2026年7月11日）
- `en/GOVERNANCE.md`・`en/CHANGELOG.md`・`en/CREDITS.md`・`en/evidence.md` を新設。
- `en/HISTORY.md` を新設。全文訳ではなく要約版とし、冒頭に「日本語版が正本、詳細は日本語を参照」の旨を明記。
- README.md / en/README.md の構成表を更新し、各英語版へのリンクを追加。
- `evidence/aaap-articles-draft.md` を新設。2005年の「アスキーアート保護協会（仮）」定款草案について記録。当該草案は本家「NPO法人アスキーアート保護協会（AAAP）」自体の定款ではなく、別の有志団体によるものである旨を明記。
- `evidence/netts-japan-email.md` を新設。2005年のネッツジャパン社とのメールのやり取りについて、Wikipediaでは「リンク切れ」とされていたが、atwiki上に現存していることを確認。2019年時点のWayback Machineスナップショットも合わせて記録し、長期間存在し続けていたことを確認。
- `evidence/netts-japan-email-full.md`・`evidence/aaap-articles-draft-full.md` を新設。上記2件の全文を原文のまま保存し、要約版から相互参照リンクを追加。
- `evidence/release.md` を新設。v1.0公開時（GitHub push・Wayback Machineスナップショット・X／Facebook告知）の記録を追加。
- `evidence/README.md` に上記各ファイルへの参照を追加。
- v1.0本体（AAAPS-v1.md等の規範）の内容には変更なし。

## v1.0
First public release.
- ChatGPTさんの最終査読を受け、軽微な追記を反映：en/README.mdに「canonical documents」を一度だけ併記、LICENSE.mdに"This file exists for repository tooling compatibility."を追記。

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

---
最新改訂日：2026年7月11日
