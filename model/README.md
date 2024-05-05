# 모델 목록

- 실험1 (xBD_2.ipynb)
```md
- 프로젝트 설명
- Accuracy: 96.62%
- MIoU: 94.08
- F1 스코어: 0.639
- 활성화 함수 sigmoid
- binary_crossentropy 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1799, val: 1000, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train accuracy
```

- 실험2 (xBD_3.ipynb)
```md
- Accuracy: 96.92%
- MIOU: 94.08 -> 96.80
- F1 Score: 0.705
- 활성화 함수 sigmoid
- binary_crossentropy 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train accuracy
```

- 실험3 (xBD_4.ipynb)
```md
- Accuracy: 96.51%
- MIOU: 96.38
- F1 Score: 0.666
- 활성화 함수 sigmoid
- binary_crossentropy 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 10
- ModelCheckpoint.saveBestOnly train accuracy
```

- 실험4 (xBD_5.ipynb)
```md
- Accuracy: 96.72%
- MIOU: 96.59
- F1 Score: 0.698
- 활성화 함수 sigmoid
- binary_crossentropy 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 50
- ModelCheckpoint.saveBestOnly train accuracy
```

- 실험5 (xBD_6.ipynb)
```md
- Accuracy: 96.67%
- MIOU: 96.55
- F1 Score: 0.685
- 활성화 함수 sigmoid
- binary_crossentropy 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train val_loss
```

- 실험6 (xBD_7.ipynb)
```md
- Accuracy: 93.78%
- MIOU: 93.60
- F1 Score: 0.477
- 활성화 함수 sigmoid
- Dice loss 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train val_loss
```

- 실험7 (xBD_8.ipynb)
```md
- Accuracy: 94.91%
- MIOU: 94.78
- F1 Score: 0.500
- 활성화 함수 sigmoid
- Jaccard 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train val_loss
```

- 실험8 (xBD_9.ipynb)
```md
- Accuracy: 0.06%
- MIOU: 0.0317e-07
- F1 Score: 0.112
- 활성화 함수 sigmoid
- Focal 손실함수 적용
- 이미지 크기 512로 훈련
- train: 1866, val: 933, test: 항상 933
- epoch: 20
- ModelCheckpoint.saveBestOnly train val_loss
```
