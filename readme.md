## 説明

* 麻雀における(3n+1)卓(12n+3)人(4n+1)戦（総当たり戦）の卓組を置いています。
* 全戦を行っても同じ2人が複数回同卓することはありません。
* 現在、n=3からn=10（10卓から31卓）における卓組があります。
* 各卓組は縦軸がプレイヤー、横軸が対戦、成分が卓番号を指します。
* 卓番号はn=3,4（10,13卓）のものは0から振っており、他は1から振っています。
* プログラムは今後公開するかもしれません。

### Format

* The digits on the filename indicates the number of tables.
* Each line corresponds to a player.
* Each column corresponds to a session.
* The intersection of a line (player) and column (session) indicates the number of the table to which the player goes in the session.
