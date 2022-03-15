---
sidebar_position: 7
---

# CSVデータ説明

| 列名                         | 項目        | 詳細                |
| -------------------------- | --------- | ----------------- |
| Timestamp                  | Timestamp | Timestamp         |
| participantId              | 被験者ID     | 被験者ID             |
| Elec                       | 電気量       | 電気量               |
| Sleep                      | AIによる推論結果 | 睡眠している確率          |
| Aircon                     | AIによる推論結果 | エアコンがついている確率      |
| InHome                     | AIによる推論結果 | 家にいる確率            |
| Change\_Lifestyle          | 異常アラート    | AIによるアラート(生活変調)   |
| Heatstroke                 | 異常アラート    | AIによるアラート(熱中症)    |
| Anomaly                    | 異常アラート    | AIによるアラート(異常)     |
| Sleep\_Alert               | 異常アラート    | 睡眠アラート            |
| Electricity\_Alert         | 異常アラート    | 電気量アラート           |
| Tmax\_Alert                | 異常アラート    | 電気量アラート2          |
| Tmax\_active               | パラメータ     | 1 - (15) - (16)   |
| Tmax\_nonactive            | パラメータ     | 非アクティブな時間の割合      |
| Tmax\_tmax                 | パラメータ     | アクティブな時間が続いた時間の割合 |
| anomaly\_thr               | パラメータ     | 異常値スコアの閾値         |
| cls\_thr                   | パラメータ     | 生活変調スコアの閾値        |
| heatst\_temp               | パラメータ     | 熱中症異常アラートの気温      |
| heatst\_st                 | パラメータ     | 熱中症監視開始時刻         |
| heatst\_en                 | パラメータ     | 熱中症監視終了時刻         |
| elec\_coef                 | パラメータ     | 電気量アラートの係数        |
| cont\_sleep                | パラメータ     | 睡眠継続時間            |
| wakeup\_int                | パラメータ     | 起床時間              |
| wakeup\_dif                | パラメータ     | 過去の起床時間との差分       |
| Min(Elec)                  | 電気量       | 電気量の最小値           |
| Distance (Anomaly)         | 異常スコア     | 異常スコア(異常値)        |
| Distance (ChangeLifeStyle) | 異常スコア     | 異常スコア(生活変調)       |
| def\_baseline              | ベースライン    | ベースライン            |
| baseline\_1                | ベースライン    | 1月のベースライン         |
| baseline\_2                | ベースライン    | 2月のベースライン         |
| baseline\_3                | ベースライン    | 3月のベースライン         |
| baseline\_4                | ベースライン    | 4月のベースライン         |
| baseline\_5                | ベースライン    | 5月のベースライン         |
| baseline\_6                | ベースライン    | 6月のベースライン         |
| baseline\_7                | ベースライン    | 7月のベースライン         |
| baseline\_8                | ベースライン    | 8月のベースライン         |
| baseline\_9                | ベースライン    | 9月のベースライン         |
| baseline\_10               | ベースライン    | 10月のベースライン        |
| baseline\_11               | ベースライン    | 11月のベースライン        |
| baseline\_12               | ベースライン    | 12月のベースライン        |