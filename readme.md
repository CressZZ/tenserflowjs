# AI, ML, DL
- `AI` (Artificial Intelligence) > `ML` (machine learning) > `DL` (deep learning)

# 머신 러닝
- 데이터를 사용하여 수학 알고리즘으로 값을 구하는 것 
    - y = ax + b 에서 a, b 값
- `Keyword` : 추론 
    - 정답을 원하는게 아니다.
    - 100% 확률로 맞추는게 아니라, 100%에 가까운 것을 맞추는 것이다. 
- 단일 Layer 형태
- 제이쿼리를 쓴다는 느낌

# 딥 러닝
- 다층 Layer 형태
- 머신러닝과 코딩 방식이 다르다
- 제이쿼리 그리드를 쓴다는 느낌 

# TensorFlow.js
- A Javascript library for training and eploying ML odels in the browser and on Node.js
- 개발: 구글
- 발표: 2018.04
- 라이센스: 오픈소스
- 머신러닝
- https://js.tensorflow.org/
- 기존에 파이썬으로 만들어진 TensorFlow Model을 컨버팅 할 수 있다. 
- 브라우저에서 연결괸 데이터를 통하여 다시 학슴 가능

# Tensorflow.js 구성
- Tnsorflow.js
    - Core: ML, DL Core
    - Layers: Depp Learning을 위한것 
    - Conveter: Python, Keras TF (레이어스)
- Node: Node.js (CPU 사용)
- GPU, TPU: WebGL(브라우저) (GPU 사용)

# Converter
- Python, Keras 연동

# Tensor
- 계산 결과, 함수 이름, Tensor 연결
```js
const one = tf.scalar(1),
      two = tf.scalar(2),
      five = tf.scalar(5);

tf.add(one, two).div(five)

```

# 선형 그래프
- y = wx + b
## 3대 요소
- 가중치
- 손실함수
- 바이어스

# 분류
- 속하는 클래스 예측

# 딥러닝 시작
- ex) 손글씨 숫자 인식

# Overfitting
- 너무 딱 맞으면 좋지 않다.
- 머신러닝과 수학 차이.



