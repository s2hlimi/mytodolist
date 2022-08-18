# My to do list

![image](https://user-images.githubusercontent.com/108657283/185281989-10963a21-af7d-450d-80e4-6add64e263ab.png)
---

## 구현해야 될 기능
- UI 구현하기
- Todo 추가 하기
- Todo 삭제 하기
- Todo 완료 상태 변경하기 (완료 ↔ 진행중)
---

## 과제에 요구되는 사항 
1. 제목과 내용을 입력하고, [추가하기] 버튼을 클릭하면 Working에 새로운 Todo가 추가되고 제목 input과 내용 input은 다시 빈 값으로 바뀌도록 구성해주세요.
2. Todo의 isDone 상태가 true이면, 상태 버튼의 라벨을 취소, isDone이 false 이면 라벨을 완료 로 조건부 렌더링 해주세요. 
3. Todo의 상태가 Working 이면 위쪽에 위치하고, Done이면 아래쪽에 위치하도록 구현합니다.
4. Layout의 최대 넓이는 1200px, 최소 넓이는 800px로 제한하고, 전체 화면의 가운데로 정렬해주세요.
5. 아래 이미지의 폴더 구조와 동일하게 구현하고 컴포넌트 구성도 똑같이 나눠서 구현해주세요.
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/533e8a8e-a4a5-41c7-9d40-b26a285afbd2/Untitled.png)
---

## Hint
- 사용한 hook은 오직 useState
- 기능 구현을 위해 생성한 함수는 2개 입니다. `onChangeHandler` , `onSubmitHandler`
- 사용한 javascript 내장 메서드는 `map`, `filter` 입니다.
- todo의 initial state는 `{id: 0, title: “”, body: “”, isDone: false}` 입니다.
