# AIFFEL Campus Online 5th Code Peer Review
- 코더 : 조대희
- 리뷰어 : 박영준


# PRT(PeerReviewTemplate) 
각 항목을 스스로 확인하고 토의하여 작성한 코드에 적용합니다.

- [O] 코드가 정상적으로 동작하고 주어진 문제를 해결했나요?
  
- [O] 주석을 보고 작성자의 코드가 이해되었나요?
  > 주석에 따라 컴프리헨션 구간과 제너레이터 구간을 보고
  > 각 구간의 지정된 함수의 역할을 이해했습니다
- [O] 코드가 에러를 유발할 가능성이 없나요?
  > 제너레이터 구간에서 영역 지정을 잘못할 경우 이터러블 객체를 찾을 수 없다는
  > 오류가 발생할 수 있지만 현재의 코드에서는 오류는 볼 수 없습니다.
- [O] 코드 작성자가 코드를 제대로 이해하고 작성했나요?
  > 예시와 기본 입력값을 기준으로 각 함수에 역할에 대한 이해를 가지고
  > 제대로 분할된 기능을 구현하고 있습니다.
- [O] 코드가 간결한가요?
  > 12줄 남짓의 코드를 통해 지연시간과 제너레이터 영역의 함수까지 간결하게 볼 수 있습니다

# 예시
1. 코드의 작동 방식을 주석으로 기록합니다.
2. 코드의 작동 방식에 대한 개선 방법을 주석으로 기록합니다.
3. 참고한 링크 및 ChatGPT 프롬프트 명령어가 있다면 주석으로 남겨주세요.
```python
# 사칙 연산 계산기
class calculator:
    # 예) init의 역할과 각 매서드의 의미를 서술
    def __init__(self, first, second):
        self.first = first
        self.second = second
    
    # 예) 덧셈과 연산 작동 방식에 대한 서술
    def add(self):
        result = self.first + self.second
        return result

a = float(input('첫번째 값을 입력하세요.')) 
b = float(input('두번째 값을 입력하세요.')) 
c = calculator(a, b)
print('덧셈', c.add()) 
```
