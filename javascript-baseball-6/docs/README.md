# Functional Specification

### baseBall

#### Number

- [x] 입력한 수에 대한 결과를 볼, 스트라이크 개수로 표시
- [x] 3자리 숫자중 같은 수 전혀 없으면 낫싱
- [x] 위 과정 반복후 맞추면 종료

사용자

- [x] 숫자 입력시 3자리 숫자가 중복되지 않게 입력하기
- [x] 숫자 입력시 3자리 숫자를 넘어가지 않게 입력하기

컴퓨터

- [x] 1-9 사이의 랜덤숫자 생성
- [x] 잘못된 값 입력시 `throw` 로 예외 발생후 종료처리
- [x] 종료후 1번으로 재시작
- [x] 종료후 2번으로 완전종료
