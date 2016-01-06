## 説明

* 麻雀における(3n+1)卓(12n+3)人(4n+1)戦（総当たり戦）の卓組を置いています。
* 全戦を行っても同じ2人が複数回同卓することはありません。
* 各卓組は縦軸がプレイヤー、横軸が対戦、成分が卓番号を指します。
* 卓番号はn=3,4（10,13卓）のものは0から、他は1から振っています。
* プログラムは今後公開するかもしれません。
* [ここ](http://utmj-haku.sakura.ne.jp/taku/taku.html)にも同じものを掲載しています。
* 現在ある卓組
 * n=3  10卓 40人13戦
 * n=4  13卓 52人17戦
 * n=5  16卓 64人21戦
 * n=6  19卓 76人25戦
 * n=7  22卓 88人29戦
 * n=8  25卓100人33戦
 * n=9  28卓112人37戦
 * n=10 31卓124人41戦

### Format

* The digits on the filename indicates the number of tables.
* Each line corresponds to a player.
* Each column corresponds to a session.
* The intersection of a line (player) and column (session) indicates the number of the table to which the player goes in the session.
