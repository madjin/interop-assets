2019/12/27 おめが(Twitter @Omegamega/VRC Omegamega/Discord omegamega#1650)


■概要
VRChat内での展示イベント用の展示ブースキットです
落選マーケットのフォーマット(4m x 4m x 5m)で作成しています。
同フォーマットのVケットや、独自の展示イベント、その他VRCワールドやゲーム等での用途を想定しています

軽量ローポリ、Questでの動作も確認済み


■内容Object詳細

SampleWorldをロードすると、とりあえずわかりやすいかと思います


[Rich]CircleName_CircleOwner.prefab
 回転する看板、付属のライト類を設置した、比較的リッチなバージョン
 こんな感じにできますの参考用に。

[Lite]CircleName_CircleOwner.prefab
 最小限の、机、ポップがある状態。


Spotlight
 Spotlightを使った照明です。看板や展示デスク周辺を照らす、といった用途に向いています
Barlight
 MaterialのEmissionを使った照明です。ボヤーッと光らせる用途にどうぞ


シェーダーはStandardシェーダーを想定しています。
Questの場合は、代わりにVRChat/Mobile/StandardLiteシェーダーを適用すると良いでしょう


■Tips

・テクスチャは2048x2048で作ってありますが、PC向けに解像度が不足する場合は4096x4069にして使うこともできます。
　その場合はファイルサイズに注意しましょう
・Emissionテクスチャはあえて低解像度にしてあり、容量を削ってます

・ライト類、机はコピーして複数置けます


■ライセンス

CC0 1.0 Universal (CC0 1.0)
Public Domain Dedication
https://creativecommons.org/publicdomain/zero/1.0/

ブース/ワールド作成・投稿・動作確認・運営の目的において
packageの再配布・改変・一部のみの利用・VRChat上での公開(public/private問わず)を含め、無制限に利用できます。

作者または著作権者は、ソフトウェアに関してなんら責任を負いません。