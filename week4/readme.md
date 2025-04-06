
만들고 싶은것

- 알아서 enemy를 움직이는 ai
- enemy들이 스폰하게 만들기
- enemy 하나에게 카메라 고정하는 ‘카메라 고정’
- 몬스터가 죽었을때 힐아이템 드롭, 경험치 획득

---

일단 enemy가 스스로 움직이게 하는 동작을 찾아준뒤

블렌드 스페이스(BS)

애니메이션 블루 프린트(ABP)

를 이용해서 

enemy 캐릭터의 행동을 자연스럽게 만들어보자

먼저 속도에 따라 걷기→ 달리기가 바뀌는 BS를 만든다.

![image](https://github.com/user-attachments/assets/c86ce28d-c08b-4d80-93ea-1b9f8e2955cf)


이후

사용할 캐릭터의 abp를 복사해서 enemy_abp로 만들어준다.

![image (1)](https://github.com/user-attachments/assets/d0b7d9e1-183a-46a0-ad03-ac71d5367408)
![image (2)](https://github.com/user-attachments/assets/e41e10d4-318a-42c4-b9bf-e54862d1c947)
