お部屋レスキュー！ Squadbeyond差し替えコード（2026-10-05）

HTMLエディターの各欄を以下の内容で置き換えてください。
1. Javascript Head：Javascript-Head.html
2. CSS：空欄（CSS.txt）。保存エラーを避けるため外部CSSを読み込みます。
3. HTML：HTML.html の全文
4. Javascript Body：Javascript-Body.html
以前のゲーム用JS・CSSの読み込みは外し、二重実行を避けてください。
広告計測タグなど、このLP以外の設定は維持してください。

画像、ゲーム本体、CSS、JSは公開GitHub PagesのURLから読み込みます。
HTML部分はSquadbeyondのネイティブ要素です。ゲームのみiframeで表示します。
CTAの遷移先は公式LPです。既存のSquadbeyond計測リンクがある場合は、HTML内の公式LPリンク5箇所を既存の計測URLへ置き換えてください。
本提案はSquadbeyond管理画面への直接反映は行っていません。公開前にプレビューでゲーム完了、途中終了、CTA遷移と計測を確認してください。

修正内容
・終了後の先頭に「自分サイズの家財保険」「保険期間2年・一時払7,000円〜」を同時表示。
・各ステージの「でも…」を36〜48pxの別行で強調。結果表示は2秒から5秒に延長。
・不動産会社経由で加入した保険の見直し・切り替えによる保険料節約の可能性を追加。
・初期画面で商品説明を見せない仕様を維持。

商品条件確認元：https://www.7-insurance.jp/lp/sej_mysizekazai/
