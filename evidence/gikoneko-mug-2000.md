# ぎこねこマグカップ初版 原稿ファイル（2000年）

2000年10月5日にAdobe Illustrator 8.0.1で作成された原稿ファイル3点（gikoneko00-2000-10-05.ai／gikoneko01-2000-10-05.ai／gikoneko02-2000-10-05.ai）とプレビュー画像1点（gikoneko01-2000-10-05.jpg）が、CD-Rバックアップより発掘された。ファイルヘッダーの `%%For: (giko neko) (Strangeworld)` 記載により、あやしいわーるど発の制作物であることが確認できる。

## ファイル一覧と作成日時

PostScriptヘッダーの `%%CreationDate` より。ファイル名はISO 8601形式の作成日を付与して統一（元ファイル名は括弧内に記録、内容は無加工）。

- gikoneko01-2000-10-05.ai（元：gikoneko01.ai）：2000-10-05 20:47
- gikoneko00-2000-10-05.ai（元：gikoneko00.ai）：2000-10-05 20:48
- gikoneko02-2000-10-05.ai（元：gikoneko02.ai）：2000-10-05 20:56
- gikoneko01-2000-10-05.jpg（元：gikoneko01.jpg）：プレビュー画像（742×577px）

ファイル名の連番（00→01→02）と保存時刻の順序（01→00→02）が一致しない点は、解釈を加えずそのまま記録する。

## 技術的検証結果

- gikoneko00.aiとgikoneko02.aiは、パス構成命令数（curveto 6892／moveto 403／lineto 1355／fill 375）および非白領域の形状が完全に一致する。両ファイルとも外部フォント参照を持たない。テキスト要素は全てアウトライン化済みであることを意味する。地色のみ異なる（00＝ティール系、02＝黒系）色違い展開と判断できる。
- gikoneko01.aiはパス構成命令数が大幅に少なく（curveto 59／moveto 66／lineto 266／fill 38）、外部フォント参照（ForteMT, Helvetica, MS-Mincho, MS-UIGothic, RFSirius-Md系）を保持したままである。テキストがアウトライン化されていない別系統のファイルと考えられる。

## チェックサム

| ファイル | SHA-256 | MD5 |
|---|---|---|
| gikoneko00-2000-10-05.ai | `1a50cc7484b11e6868a76740419e2af1ce694cd23c92dae7fcebfcd494075f74` | `fceaae877836479a1a57983dbf4fd807` |
| gikoneko01-2000-10-05.ai | `ef1bc6f690e4e2c459e7a994c5a96b0db275ad0b0a36dcbdda53b2ccb30f59da` | `ae13e4e91007e1a695f343b74fbf7336` |
| gikoneko02-2000-10-05.ai | `4d18aae084c69efc948adff795ba2e8310cfedf6d7b0c28b04462fb28bfb89cb` | `cf4aa10025ecbd942ab281b4591ffb77` |
| gikoneko01-2000-10-05.jpg | `c3022da3f28c274c7703f9f4eb9ce016d3932304a7a4ea1c8069a4394e6c0485` | `57e6305fb173d065b4e840e530088898` |

原本は無加工のまま保存している。

## 原本zip（証拠性担保）

発掘時のzipファイルそのものを `evidence/gikoneko-mug-2000/gikomag.zip` として、ファイル名を含め無加工のまま保存する。上記4ファイルはこのzipからの展開物である。

| ファイル | SHA-256 | MD5 |
|---|---|---|
| gikomag.zip | `8bde88330e0fb07dda9d00dbfcfa6c35c57b89a071d1fb6881c910632577140a` | `132c28d800f41c91e7cb7d4e0ec442bf` |
