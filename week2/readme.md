3/12

게임에 쓸(또는 그냥 개발할때만쓸) 빈필드 만들기

플레이어블 캐릭터 만들기

![스크린샷(1791)](https://github.com/user-attachments/assets/b1549cbd-cbb9-43eb-9400-6035cfcadbfa)


- 언리얼엔진 무료 에셋으로 얻은 칼

---

3/15

2주차에 구현하고자 하는것

- 플레이어블 캐릭터 스탯만들기
- 캐릭터의 손에 칼을 장비하기
- 캐릭터에게 공격모션 넣기
- 적 더미에게 데미지가 들어가는지 확인하기

char_data 파일을 만들고 

우클릭→블루프린트→구조체

이곳에서 캐릭터 스탯을 설정

![스크린샷(1789)](https://github.com/user-attachments/assets/6314c787-ebb2-4a67-afd1-ece5da1ea4aa)


이후 우클릭 → 데이터 테이블 검색

Player_data 구조체와 연결해준다.

![스크린샷(1790)](https://github.com/user-attachments/assets/2727d667-70d4-445b-b03b-af027c7a8bb0)


(나중에 사용)

사용하고자하는 공격모션을 구했다.

하지만 애니메이션을 바로 임포트할 수 없었기 때문에

Mixamo converter를 이용했다.

https://terribilisstudio.fr/?section=home#close <- 사이트

---

3/17

![스크린샷(1787)](https://github.com/user-attachments/assets/ba3eabf3-6847-46d4-91be-df3d16f66c40)

![스크린샷(1788)](https://github.com/user-attachments/assets/78c3e87e-fdd2-458b-a884-c04aa4ddc516)

![스크린샷(1792)](https://github.com/user-attachments/assets/3fc463c4-78c7-49ae-866b-12a26b25005d)

애님 노티파이 스테이트를 만들어 노티파이 begin, end 설정

sword trace 그래프를 만들어 칼을 휘두르는 모션에서 원하는 타이밍에 sphere가 생성되어 닿으면 데미지가 들어가도록 설정

실행되는 애니메이션이 길어서 녹화를 이용해 줄임


다음으로 만들것 : 몬스터

플레이어와 마찬가지로 enemy_data 구조체와 data_table 생성

몬스터에 구현해야할것

- 더미에 체력을 넣어서 체력이 줄어드는지 확인
    - 체력바 위젯을 넣어야겠다.
