# Chapter 01 연습문제

1. [그림 1-7]의 선형분리 불가능한 상황을 선형분리 가능한 상황으로 변환해 주는 자신의 함수를 고안하여 제시하시오.

2. 다음 훈련집합을 3차원 공간에 그리고, 선형분리 가능 여부와 그 이유를 제시하시오.

3. [예제 1-1]에서 $\Theta=(w,b)^{T}=(-0.1,4.0)^{T}$ 일 때 목적함수의 값을 계산하시오. $b$를 4.0으로 고정한다면 $w$를 얼마로 해야 목적함수가 최저가 되는지 기술하시오.

$$
x_{1} = 
\begin{pmatrix}
0 \\ 0 \\ 0
\end{pmatrix}, 
x_{2} = 
\begin{pmatrix}
0 \\ 1 \\ 1
\end{pmatrix}, 
x_{3} = 
\begin{pmatrix}
1 \\ 1 \\ 1 
\end{pmatrix}, 
x_{4} = 
\begin{pmatrix}
1 \\ 0 \\ 1
\end{pmatrix}, 
x_{5} = 
\begin{pmatrix}
0 \\ 0 \\ 1
\end{pmatrix}, 
x_{6} = 
\begin{pmatrix}
0 \\ 1 \\ 0
\end{pmatrix}
$$

$$
y_{1} = 1, y_{2} = 1, y_{3} = 1, y_{4} = -1, y_{5} = -1, y_{6} = -1
$$

4. [그림 1-10]은 4차원 특징 공간을 여러 개의 2차원 조합으로 나누어 그린 것이다. 4개 특징 중에 2개만 사용해야 한다면 어느 쌍을 사용할지 개략적으로 설명하시오.

5. 종이에 "대한민국"을 10개 쓰시오. 한 번은 최선을 다해 비슷한 모양이 되도록 쓰고, 다음에는 최대한 서로 다른 모양이 되도록 쓰시오. 결과를 가지고 필기 한글 인식 문제의 난이도에 대한 견해를 제시하시오.

6. [표 1-1]에서 새로운 기준을 개발하고 사람과 기계의 학습을 비교하시오.

7. <a href="http://yann.lecun.com/exdb/mnist/">http://yann.lecun.com/exdb/mnist/</a> 에 접속하면 [Ciresan2012]가 MNIST 필기 숫자 데이터베이스에서 현재 최고 성능을 보인 논문이라는 사실을 알 수 있다. 이 논문은 테스트 샘플 10,000자 중 틀린 23자를 제시한다. 논문을 참조하여 틀린 샘플을 제시하고, 이들 오류에 대한 자신의 견해를 제시하시오.

8. UCI 리퍼지토리에서 특징 벡터의 차원이 100 이하인 데이터베이스 2개, 100보다 크고 1000이하인 것 2개, 1000보다 큰 것 2개를 선정하여 부류 개수, 특징 개수, 샘플 개수를 조사하시오.

9. 뇌 질환과 관련한 데이터베이스를 조사하고, 많이 쓰이는 2가지를 골라 데이터베이스 내용에 대해 기술하시오.

10. 이 책의 참고문헌을 주의 깊게 살펴보면 기계 학습을 선도하는 논문은 주로 저널보다 학술대회에서 발표된다는 사실을 알 수 있다. 예를 들어, NIPS (Nueral Information Processing Systems) 와 ICML (International Conference on Machine Learning) 은 기계 학습의 혁신적인 아이디어와 혁신적인 실험 결과가 주로 발표되는 주요 학술대회이다. 이러한 현상은 컴퓨터 공학의 학문 특성에 따라 일어나는데, 어떤 특성인지 조사하고 자신의 의견을 덧붙여 기술하시오.
- Hint: 위키피디아에서 <a href="https://en.wikipedia.org/wiki/Computer_science">Computer Science</a> 참조

11.  앱인벤터 (AppInventor) 는 안드로이드 앱을 개발하는 데 쓰는 언어인데, 비전공자들이 쉽게 배울 수 있는 장점이 있다. 앱인벤터는 기계 학습과 관련된 컴포넌트를 몇 가지 제공하는데, 성능이 뛰어나다. 이들 컴포넌트를 조사하시오. 또한 성능 평가 기준을 세우고 테스트용 앱을 제작하여 컴포넌트의 성능을 평가 분석하시오.
- Hint: <a href="http://appinventor.chonbuk.ac.kr">http://appinventor.chonbuk.ac.kr</a> 참조
- 책 저자 홈페이지, 2021년 4월 8일 기준 관련 내용 찾을 수 없음

12.  다음은 기계 학습으로 제작된 인공지능 시스템인데, 웹을 통해 데모 서비스를 제공한다. 성능을 기준으로 스스로 개발하고 성능을 측정 분석하시오. 특히 사람의 능력과 견주었을 때 우열에 대한 자신의 생각을 제시하시오.
- 영상 주석 달기 (<a href="http://deeplearning.cs.toronto.edu/i2t">http://deeplearning.cs.toronto.edu/i2t</a>) (작동중)
- 자연 영상 인식 (<a href="http://demo.caffe.berkeleyvision.org">http://demo.caffe.berkeleyvision.org</a>) (작동안함)
- 필기 흉내내기 (<a href="http://www.cs.toronto.edu/~graves/handwriting.html">http://www.cs.toronto.edu/~graves/handwriting.html</a>) (페이지는 열리나 작동이 느림/안됨)
- 구글 번역 (<a href="https://translate.google.com/">https://translate.google.com/</a>)
- 구글 음성 인식 (<a href="https://google.com">https://google.com</a>)
- 사진을 화풍으로 변환 (<a href="http://deepdreamgenerator.com">http://deepdreamgenerator.com</a>)

13. 1.8.3절의 사회적 전망을 참고하여, 인공지능의 현재와 미래 전망에 대한 자신의 견해를 밝히시오.