﻿#開発環境
Android Studio 2.1<br>
Android v4.3<br>
nexus 7<br>
<br>
#状態
鋭意更新中<br>
<br>
#遷移
2016/8/11 大まかなプロトタイプ完成<br>
2016/8/15 Optionでの変数値の保持 by Shun<br>
2016/8/15 デバッグ用のbeat円の表示 by Ryo<br>
2016/9/02 タッチ座標での画面遷移 by Shun<br>
2016/9/06 Backの画像配置実装 by Shun<br>
<br>
#予定
画面遷移だけ(完了)<br>
↓<br>
メニュー画面とか書く<br>
グラフィックの表示とかも<br>
↓<br>
タッチ位置とか検出するの実装<br>
↓<br>
タッチ座標からの各種値入手&算出←いまここ<br>
↓<br>
音ライブラリとの統合<br>
↓<br>
メモリ食い具合調整<br>
使用性の向上
↓<br>
完成
<br>
#やりたいこと
・縦持ち→横持ちの遷移(水の画面を横持ちする場合)<br>
・水面グラフィック ← 2次元エフェクトで妥協<br>
・音の処理&加工<br>
・UIの向上<br>
・各種値の入手&算出システム<br>
・動作の安定化<br>
<br>
#Help!
Canvasで波の表示を行うとボタンが隠れる<br>
 →表裏の画面遷移とOptionの呼び出し不可 要対策<br>
タッチ座標でintent呼んだらいける(?)</br>
 →いけました やったぜ。<br>
Canvasの波の上に画像表示させるの<br>
 →システム系のレイヤ使えばいいかもしれんけど未確認&反応するか不明<br>
 →GraphicViewの編集で完遂 やったぜ。<br>
<br>
