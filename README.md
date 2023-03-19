# Transformer

- 논문 : [arXiv](https://arxiv.org/pdf/1706.03762.pdf)

2017년 구글 연구팀이 NIPS에 공개한 딥러닝 아키텍처

기계번역과 같은 시퀀스 투 시퀀스 작업을 수행하기 위해 만들어진 모델입니다.

기존 모델들과는 달리 RNN이나 CNN 없이 오직 어텐션 메커니즘을 기반으로 설계된 딥러닝 아키텍처입니다.

어텐션 메커니즘은 시퀀셜 데이터의 long-range dependence를 효과적으로 학습해 기계번역에서 뛰어난 성능을 보여주었습니다.




### Architecture

<img src="Transformer.assets/2022-07-16-04-15-40-image.png" title="" alt="" width="340">
