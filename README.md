# React 입문주차 Todo List 과제



지난 번 버킷리스트때 추가로 구현해본 삭제기능에서 발생했던 문제점들이
이번 과제를 진행하면서 해결이되었다. 고유값이 없기때문에 목록을 삭제 후 추가를하면 기존 번호가 중복되면서 엉뚱한것이 삭제되고 수정되었 던 것
이번 과제통해 지난 오류를 이해할 수 있었다. (아직 구현은 안해봄)

## app.js

- pages 폴더 내 TodoList.js와 연결 됨

## pages / TodoList.js

- components /Layout, Header, Form, List 와 연결 됨

## components

- Layout : Todo List 전체 영역

- Header : 헤더

- Form : insert form component

- List : 추가한 카드와 완료된 카드 나뉘어진 공간
Todo와 연결 됨

- Todo : 카드 삭제, 취소, 완료 기능구현 공간
