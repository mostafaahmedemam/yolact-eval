# yolact-eval

I evaluate my yolact trained model with custom dataset, and observe performance of the model.

## Output

1- Colab <br/>

| Trial                                | fps   | time |
| ------------------------------------ | ----- | ---- |
| multi-frame:8 , backbone: resnet-50  | 11.64 | XX   |
| multi-frame:20 , backbone: resnet-50 | 14.92 | XX   |
| multi-frame:50 , backbone: resnet-50 | 13.60 | XX   |

2- Local Machine "GTX 980" <br/>

| Trial                                | fps | time |
| ------------------------------------ | --- | ---- |
| multi-frame:2 , backbone: darknet-50 | 8.7 | XX   |
| multi-frame:4 , backbone: darknet-50 | 9.3 | XX   |

```
Observation: relation between multi-frame parameter and fps not linear, with high multi frame  fps increase until bottle-neck occured and then fps decrease again to be in range 12 fps.
```
