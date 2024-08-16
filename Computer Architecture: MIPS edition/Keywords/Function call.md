- 말 그대로 함수 호출이다.
- 함수를 호출할 땐 [[Register]] Rule에 따라 지정된 값을 저장한 뒤, 특정 [[Instruction]]을 이용해 호출한다.
- 함수를 호출할 때 [[PC(Program Counter)]]가 Program Memory의 Function 위치로 옮겨간다.
- 함수를 호출할 때 Register 중 일부는 데이터가 손실될 수 있다. 예를 들어 Temporary Register가 있다.