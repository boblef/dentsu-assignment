# K3

## Text Clustering

**十分な時間を取ることができなかったので、方針をここに示します。**

- データクリーニング
  - 重複行の確認と削除
  - トークナイズ (Text to Number)
- それぞれのデータポイント間の類似度を計算
  - X-axis: doc_id, Y-axis: Text の類似度の Plot
- トレーニングモデル
  - Plot を元にトレーニングするモデルを決定する。
  - 参考: https://towardsdatascience.com/the-5-clustering-algorithms-data-scientists-need-to-know-a36d136ef68
- ハイパーパラメーターサーチ
  - Optuna で、パラメーターサーチを行う
  - Optuna: https://github.com/pfnet/optuna
