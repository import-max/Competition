# handSignalPrediction
[Vision]
[2021 교통 수(手)신호 동작 인식 AI 경진대회](https://dacon.io/competitions/official/235806/overview/description)



## Classification Approach
|Model         |log_loss|option|
|:------------:|:------:|:----:|
|EfficientNetB2|0.5087  |      |
|EfficientNetB7| 0.1006 |    None augmentor, acc = 0.9658  |
|EfficientNetB7|0.5087  |    None augmentor, valid_set  |
|Resnet50v2    |0.2281  |      |
|Slow-Fast     |1.09    |      |
