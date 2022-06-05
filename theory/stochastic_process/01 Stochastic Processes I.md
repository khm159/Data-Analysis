## Stochastic Processes I 

[Video Lecture : MIT OpenSource](https://www.youtube.com/watch?v=TuTmC8aOQJE)


#### 1. Stochastic Process란? 

Collection of randomvariables indexed by time. 

- 확률과정의 정의 : 시간축에 대해서 연속된 확률 변수들의 집합.

descrete : $X_0$, $X_1$, .... 

continuous : $\{X_t\}$ t 가 컨티뉴얼.

- 확률과정의 대안적 정의 2: probability distribution over a space of paths. 가능한 경로를 확률분포 적으로 정함.


#### 2. 확률과정의 예 

1. 

- $f(t) = t, \forall t$ with probability 1

![ex1](images/stochastic1_ex01.png)

random 하지 않음. probability가 1. 랜덤 하지 않음.

2. 

- $f(t) = t, \forall t$ with probability 0.5

- $f(t) = -t, \forall t$ with probability 0.5

![ex1](images/stochastic1_ex02.png)

two possible paths you can take. 

대안적 정의로 보면 2개의 pathway가 존재한다고 볼 수 있음. 

서로 종속이기 때문에 다른값은 종속이기 때문에 바로 알 수 있음.

3. 

for each $t$, 

$f(t) = t$ with probability 0.5

**or**

$f(t) = -t$ with probability 0.5

![ex1](images/stochastic1_ex03.png)

각 시점마다 t가 될수도 -t가 될 수도 있음. 


4. 

Stochastic process는 다음과 같은 상황에서 쓰일 수도 있음.

어떤 시점 t를 지정하고 해당 시점의 과거의 값(관측치)들은 알고 있는 상황에서 미래의 값들을 알고 싶을 때.

예를들면, 주식 가격의 예측 등. 

(2)의 경우, f(t)를 알고 있기 때문에, 손쉽게 예측가능.

그러나 (3)은? 과거의 모든 값을 다 알고 있더라도, t나 -t가 될 것 같다는건 알지만, 미래의 예측은 사실상 어려움. 




