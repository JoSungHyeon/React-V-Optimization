# React + Vite Optimization

1. useMemo
"메모이제이션" 기법을 기반으로 불필요한 연산을 최적화 하는 리액트 훅
매번 같은 연산을 하지 않고 처음에 연산을 저장해뒀다가 사용함

2. memo
리렌더링이 불필요한곳에 사용
객체로 props를 받는곳은 추가 콜백함수 사용

3. useCallback
마운트 될때만 실행되게끔 만들어주는 리액트 훅

---
꼭 최적화가 필요한 곳만 최적화하기
ex) 유저에 행동에 따라 갯수가 변경되거나 함수들을 많이 가지고 있는 컴포넌트
---

---
기능구현 먼저 완료하고 최적화를 해야 고장 안남
---