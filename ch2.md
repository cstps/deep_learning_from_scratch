# 퍼셉트론(perceptron)
1. 다수의 신호를 입력받아 하나의 신호를 출력한다.
2. 프랑크 로젠블라트가 1975년 고안
3. 신경망(딥러닝)의 기원
4. 가중치와 임계값으로 표현
> ![perceptron](https://github.com/cstps/deep_learning_from_scratch/blob/main/CodeCogsEqn.gif)

5. 가중치와 편향 도입
> ![perceptron](https://github.com/cstps/deep_learning_from_scratch/blob/main/CodeCogsEqn-2.gif)
- 여기서는 b를 편향(bias)이라 하며 w1과 w2는 그댈 가중치
- 퍼셉트론은 입력 신호에 가중치르 곱한 값과 편향을 합하여, 그 값이 0을 넘으면 1을 출력하고, 그렇지 않으면 0을 출력
