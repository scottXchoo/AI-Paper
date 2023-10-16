# AI_Paper
> AI 논문 읽고 정리하는 레포

## 주요 AI 학회 정리
> [참고 링크](https://scholar.google.co.kr/citations?view_op=top_venues&hl=ko&vq=eng_artificialintelligence)

- NeurIPS: Neural Information Processing Systems
  - AI 및 ML 분야에서 가장 권위 있는 학회 중 하나
  - 최신 머신러닝 연구와 알고리즘에 대한 깊이 있는 논의가 이루어짐
  - 매년 12월에 개최
- ICLR : International Conference on Learning Representations
  - 딥러닝에 초점을 맞춘 가장 권위 있는 학회 중 하나
  - 특히, 표현 학습과 딥러닝에 특화된 학회
  - 매년 5월에 개최
- ICML : International Conference on Machine Learning
  - 머신러닝 분야의 가장 중요한 학회 중 하나
  - 다양한 분야에 적용되는 머신러닝 주제들을 아우르며, 각 분야의 최고 전문가들이 모여 연구 발표 및 토론함
  - 매년 7월에 개최
- AAAI : Conference on Artificial Intelligence
  - 인공지능에 관해 광범위한 주제로 토론 진행
  - 실용적인 AI 응용 분야 세션도 포함
  - 매년 2월에 개최
- ESWA : Expert Systems with Applications
- CVPR : Conference on Computer Vision and Pattern Recognition
  - 컴퓨터 비전 및 패턴 인식 분야에서 가장 중요한 학회 중 하나
  - 이미지 인식, 객체 검출, 비디오 분석 등에 대한 최신 연구 발표
  - 매년 6월에 개최
- ICCV : International Conference on Computer Vision
  - CVPR과 함께 컴퓨터 비전 분야의 최고 권위를 인정받는 학회
  - 홀수 해의 10월에 개최
### 레퍼런스
- [AI/DL/ML 주요 학회 순위 및 분류](https://soyoungpapa.co.kr/ai-dl-ml-%EC%A3%BC%EC%9A%94-%ED%95%99%ED%9A%8C-%EC%88%9C%EC%9C%84-%EB%B0%8F-%EB%B6%84%EB%A5%98/)

## 논문 간단 리뷰
### [The Forward-Forward Algorithm: Some Preliminary Investigations](https://www.cs.toronto.edu/~hinton/FFA13.pdf)
- Geoffrey Hinton(제프리 힌턴) by Google Brain
- 역전파(back-propagation)의 종말? 이제는 역전파를 사용하지 않고 신경망 모델을 학습시킬 수 있는 알고리즘 소개
- 신경망의 입력에서부터 출력까지 순전파가 진행되면서, 한 층을 통과할 때마다 지역적(local) 가중치 업데이트가 진행되는 것
- 기존의 신경망 학습법과 달리 손실(loss)을 계산하고 이를 역전파시키는 과정이 존재하지 않으며, 순전파 과정 동안 학습(train)과 추론(inference)이 동시에 진행됨
