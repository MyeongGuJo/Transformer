# Transformer

- using colab (T4 GPU)
- heads of MultiHeadAttention = 1
- \# of encoder layers = 1
- \# of decoder layers = 1

# Dataset

- 한영 번역 말뭉치_대화체
- https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=126

# Task

- ![image](https://github.com/MyeongGuJo/Transformer/assets/102133534/fc851ce0-b31e-43eb-9908-df0d6e946d2b)
- input_seq에 영어로 번역하고 싶은 한국어를 입력합니다.
- 인코더, 디코더 레이어 개수가 각각 1이라 번역을 잘 하지는 못하지만 어느정도 나옵니다.
