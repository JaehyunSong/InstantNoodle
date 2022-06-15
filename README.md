# InstantNoodle
インスタントラーメンのデータセット

* 作成途上のデータセットです。
* 収集対象: 日清 / エースコック / サンヨー食品 / 東洋水産 / まるか食品 / 明星
* データ収集日
   * 日清: 2022/05/26 - 2022/05/27
   * エースコック: 2022/05/27 - 2022/05/28
   * サンヨー食品: 2022/05/28 - 2022/05/29
   * 東洋水産: 2022/05/29 - 2022/06/14
   * まるか食品: 2022/06/14
   * 明星: 2022/06/14 - 2022/06/15

## 詳細

|変数名|説明|単位|備考|
|:---|:---|:---|:---|
|`ID`||||
|`メーカー`|会社名|||
|`タイプ`|カップ / 袋|||
|`商品名`|公式HPより|||
|`汁`|汁の有無|||
|`容量`|麺を含む容量|g||
|`麺量`|麺のみの容量|g||
|`熱量`||kcal||
|`たんぱく質`||g||
|`脂質`||g||
|`炭水化物`||g||
|`食塩_麺かやく`|食塩相当量 (麺・かやく)|g||
|`食塩_スープ`|食塩相当量 (スープ)|g|汁なしの場合は欠損|
|`ビタミンB1`||mg||
|`ビタミンB2`||mg||
|`カルシウム`||mg||
