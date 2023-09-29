# AI_Paper
AI 논문 읽고 정리하는 레포

### [The Forward-Forward Algorithm: Some Preliminary Investigations](https://www.cs.toronto.edu/~hinton/FFA13.pdf)
- Geoffrey Hinton(제프리 힌턴) by Google Brain
- 역전파(back-propagation)의 종말? 이제는 역전파를 사용하지 않고 신경망 모델을 학습시킬 수 있는 알고리즘 소개
- 신경망의 입력에서부터 출력까지 순전파가 진행되면서, 한 층을 통과할 때마다 지역적(local) 가중치 업데이트가 진행되는 것
- 기존의 신경망 학습법과 달리 손실(loss)을 계산하고 이를 역전파시키는 과정이 존재하지 않으며, 순전파 과정 동안 학습(train)과 추론(inference)이 동시에 진행됨
