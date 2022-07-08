# ImageRecognition

Pytorchを用いた、2、4クラス画像分類タスク。

2 and 4 classes image recognition by pytorch.

## Method
### data
Scraping from Google Image Search about

- food
- flower
- art
- ballon

each 142

### Test
- compare optimizers - adam vs SDG, adam vs Momentam SDG
- compare methods - Alex net vs classic image recognition method (AKAZE, bug of words)
- try improve accuracy by parameter search

## Summary
- Data noise affects accuracy fluctuations
- Adam converges accuracy faster than SDG
- CNN 　＞　classic image recognition method (AKAZE, bug of words)
- The more classes you have, the more difficult to solve
- Adam converged faster than Momentum SDG
- This time, I could not improve the performance of Adam network by parameter search
- What if I try another parameter search: Bayesian Optimization?


## Slide
[2 classes image recognition](https://docs.google.com/presentation/d/1sw7os1eaER9SyrXpslNNlo0D0NGOf6QV/edit?usp=sharing&ouid=108798814538205080505&rtpof=true&sd=true)

[4 classes image recognition](https://docs.google.com/presentation/d/1ahnWArrs5EfpoGgCrSFmVS6-ZfdKIULx/edit?usp=sharing&ouid=108798814538205080505&rtpof=true&sd=true)
