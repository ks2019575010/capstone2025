카메라 target lock 기능을 만듬(tab을 눌러 활성화)
아군 캐릭터의 체력,마나,경험치,레벨을 표시하는 위젯을 만듬

---

# AI

저번주에 이어서 적의 AI를 만들어보고자 한다.

블랙보드(BB)를 만들어준뒤

![image (3)](https://github.com/user-attachments/assets/4a41a572-db99-4c2f-9d87-0d7f997d7e91)


비헤비어 트리에 넣을 btt들을 만들어준다.

![image (4)](https://github.com/user-attachments/assets/51c697a8-e26f-4b37-9eff-8054b7f7f47c)


그리고 BT에서 연결

![image (5)](https://github.com/user-attachments/assets/469ac4f8-04e3-4dee-b54d-0a72c3bb6ea7)


ai 컨트롤러를 만들어주고

![image (6)](https://github.com/user-attachments/assets/cccdde42-d86d-477e-b702-8703ae1155a2)


이후 ai가 돌아다닐 수 있게

**NavMeshBoundsVolume** 을 넣어준다.

(p를 눌러 범위를 볼 수 있다)

![image (7)](https://github.com/user-attachments/assets/aa0398f2-c34b-442f-8c09-5615b1374773)


