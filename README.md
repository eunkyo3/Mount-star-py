# 문제
표준 입력으로 삼각형의 높이가 입력됩니다. 입력된 높이만큼 산 모양으로 별을 출력하는 프로그램을 만드세요(input에서 안내 문자열은 출력하지 않아야 합니다). 이때 출력 결과는 예제와 정확히 일치해야 합니다. 모양이 같더라도 공백이나 빈 줄이 더 들어가면 틀린 것으로 처리됩니다.
# 입력
5
# 출력
![image](https://user-images.githubusercontent.com/112944851/229813643-69ab6997-0810-41ff-8651-a637c00e31cc.png)
# 나의 풀이
```python
# 높이를 입력받음
x = int(input())

# 앜 설명하기 귀찮 나중에 설명함.
for i in range(x):
    for j in range(x-i-1):
        print(' ', end='')
    for k in range(2*i+1):
        print('*', end='')
    print()
```
출처: [파이썬 코딩도장 19.6문제](https://dojang.io/mod/quiz/review.php?attempt=2010413&cmid=2264)
