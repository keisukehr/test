# ユーザーの好みの変化の要因分析結果

## 分析結果

### サマリ

* {STR_IMPORTANT_FEATURES} は特に好みの変化に対する影響が大きい。

### 詳細

#### 1. モデル情報

* 最も精度の良いモデル: {BEST_MODEL_NAME}
* 精度: AUC {BEST_MODEL_AUC_SCORE} (最もF1 Scoreが高い閾値での陽性的中率 {BEST_MODEL_PRECISION})

#### 2. 特徴量のインパクト

* {STR_IMPORTANT_FEATURES} は特に好みの変化に対する影響が大きい。

![feature_impacts]({IMAGE_PATH_FEATURE_IMPACTS})

#### 3. 特徴量ごとの作用

##### ワードクラウド

![word_cloud]({IMAGE_PATH_WORD_CLOUD})

{STR_PARTIAL_DEPENDENCES}

## 分析設定

### 分析対象データ

|  項目  |  詳細  |
| ---- | ---- |
|  入力ファイル名  |  {INPUT_FILE_PATH}  |
|  レコード数  |  {N_RECORDS}  |
|  データ期間  |  {DATE_DATA_BEGIN} ~ {DATE_DATA_END}  |
|  ターゲットの割合  |  {TARGET_RATE} %  |

### モデリングの設定

|  項目  |  詳細  |
| ---- | ---- |
|  モデリングモード  |  オートパイロット  |
|  モデルの最適化指標  |  AUC  |
|  パーティションの決定方法  |  層化抽出  |
|  交差検定の分割数  |  5  |
|  ホールドアウトの割合  |  0 %  |

### DataRobot参照先

* プロジェクトID: {DR_PROJECT_ID}
* プロジェクト名: {DR_PROJECT_NAME}
