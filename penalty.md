# ペナルティについて

[目次へ戻る](/README.md)

- 鳴尾浜(先発投手が5回もたず7失点[^失点自責点] または 任意の投手が8失点[^失点自責点])
    - 当該選手が先発登板していた場合、本来の疲労値に疲労値100を加算。
    - 当該選手が救援登板していた場合、本来の疲労値に疲労値200を加算。
- [疲労](/fatigue.md)中の登板
    - 当該選手の本来の疲労値に疲労値100を加算。
    - シーズン持ち越しあり。
        - 本ペナルティ適用後、1度も疲労値0にならずに第24試合が終了した場合、第24試合終了後の疲労値(第25試合があると仮定した場合の疲労値)を次期第1試合の疲労値として引き継ぐ。
- [ケガ](/accident.md)中の出場
    - ケガ完治後、当該選手には全治10試合(固定)のケガ `ケガ悪化` が発生。
    - シーズン持ち越しあり。
        - `ケガ悪化` が完治せずにシーズンが終了した場合、合計10試合の出場停止となるよう次期第1節から `ケガ悪化` を発生させる。
- TSOB枠等、その他規約違反
    - 次の同カードの対戦で、違反者は試合開始時点から2巡の間は強振禁止。
    - [HDCP `単打育成プログラム+X`](/handicap.md/#単打育成プログラム) を選択している場合、その効果にさらに2巡の上乗せを行うこと。

[目次へ戻る](/README.md)

[^失点自責点]: MPBにおいては、自責点と失点の区別を行わない。
