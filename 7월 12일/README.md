# Show and Tell: A Neural Image Caption Generator Review

2015년도에 CVPR에서 발표된 논문 Show and Tell: A Neural Image Caption Generator 리뷰 해봄


# Main Idea
Translation model의 Architecture를 따옴
encoder 부분을 RNN이 아닌 CNN으로 바꾸어서 사용함


# Model
Target description sentence of training image의 likelihood가 maximize가 되도록 학습시킴
Single joint model 형태(CNN+RNN)
1) end-to-end system
2) Using SGD
3) Using pre-traind model(VGG)
4) Using BLEU score(모델 평가 지표)




시간상의 문제로 전체를 리뷰하지는 못함 다음주에 이어서 끝부분까지 공부한 후 리뷰 해보려고 함
-> Image caption 관련하여 공부한 후, model을 짜면 매우 좋을 듯함
