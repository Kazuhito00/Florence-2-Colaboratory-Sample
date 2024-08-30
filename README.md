# Florence-2-Colaboratory-Sample
Microsoft の軽量VLMである[microsoft/Florence-2](https://huggingface.co/microsoft/Florence-2-large)のColaboratory上でのサンプルです。<br>

# Usage
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kazuhito00/Florence-2-Colaboratory-Sample/blob/main/Florence-2-Colaboratory-Sample.ipynb)<br>
Colaboratoryでノートブックを開き、上から順に実行してください。<br>

# Task
* CAPTION：キャプション
* DETAILED_CAPTION：詳細なキャプション
* MORE_DETAILED_CAPTION：より詳細なキャプション
* OD：物体検出
* DENSE_REGION_CAPTION：高密度領域キャプション
* REGION_PROPOSAL：領域提案
* CAPTION_TO_PHRASE_GROUNDING：キャプションからフレーズへの接地
* OPEN_VOCABULARY_DETECTION：オープンボキャブラリー物体検出
* REFERRING_EXPRESSION_SEGMENTATION：参照セグメンテーション
* REGION_TO_SEGMENTATION：領域指定セグメンテーション
* REGION_TO_CATEGORY：領域→カテゴリー
* REGION_TO_DESCRIPTION：領域→説明
* OCR：単純OCR
* OCR_WITH_REGION：領域検出OCR

# Processing time reference
Google Colaboratory T4 GPU 上での処理時間計測結果(%%time使用)<Br>
1600x1066の画像を入力

| タスク | 処理時間目安 |
| --- | --- |
| CAPTION | CPU times: user 420 ms, sys: 1.1 ms, total: 421 ms<br>Wall time: 421 ms | 
| DETAILED_CAPTION | CPU times: user 978 ms, sys: 4.15 ms, total: 982 ms<br>Wall time: 981 ms | 
| MORE_DETAILED_CAPTION | CPU times: user 1.66 s, sys: 7.85 ms, total: 1.67 s<br>Wall time: 2.48 s | 
| OD | CPU times: user 2.3 s, sys: 7.84 ms, total: 2.31 s<br>Wall time: 2.3 s | 
| DENSE_REGION_CAPTION | CPU times: user 5.54 s, sys: 14.5 ms, total: 5.56 s<br>Wall time: 5.55 s | 
| REGION_PROPOSAL | CPU times: user 1.61 s, sys: 5.18 ms, total: 1.62 s<br>Wall time: 1.66 s | 
| CAPTION_TO_PHRASE_GROUNDING | CPU times: user 729 ms, sys: 2.96 ms, total: 732 ms<br>Wall time: 730 ms | 
| OPEN_VOCABULARY_DETECTION | CPU times: user 700 ms, sys: 962 µs, total: 701 ms<br>Wall time: 698 ms | 
| REFERRING_EXPRESSION_SEGMENTATION | CPU times: user 8.37 s, sys: 10.7 ms, total: 8.38 s<bR>Wall time: 8.45 s | 
| REGION_TO_SEGMENTATION | CPU times: user 6.58 s, sys: 16.7 ms, total: 6.6 s<br>Wall time: 6.61 s | 
| REGION_TO_CATEGORY | CPU times: user 341 ms, sys: 52 µs, total: 341 ms<br>Wall time: 339 ms | 
| REGION_TO_DESCRIPTION | CPU times: user 426 ms, sys: 1.91 ms, total: 428 ms<br>Wall time: 424 ms | 
| OCR | CPU times: user 917 ms, sys: 22 µs, total: 917 ms<br>Wall time: 914 ms | 
| OCR_WITH_REGION | CPU times: user 2.99 s, sys: 10.5 ms, total: 3 s<br>Wall time: 3.09 s | 

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
Florence-2-Colaboratory-Sample is under [MIT License](LICENSE).

# Note
サンプルの画像は[ぱくたそ](https://www.pakutaso.com/)様の「[雨の都市風景、 横断歩道と歩行者](https://www.pakutaso.com/20230815222post-48102.html)」「[パイクプレイスマーケットのエントランスとMediCleanseトラック](https://www.pakutaso.com/20240617157medicleanse.html)」を使用しています。
