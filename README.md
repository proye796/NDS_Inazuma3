# 이나즈마 일레븐 3 세계로의 도전!! NDS 한국어 패치 v1.0.5

배포일: 2026-11-27\
대상: 일본판 세 판 — 디 오우거 BOEJ, 스파크 BE8J, 봄버 BEZJ, 모두 revision 0

배포 ZIP에는 원본 ROM이나 패치 완료 ROM이 포함되지 않습니다. 정품에서 추출한 아래 해시와 일치하는 일본판 NDS ROM이 필요합니다. 판마다 패치가 따로 있으니 가지고 있는 판의 파일을 쓰세요.

## 지원 원본

| 파일 | 크기(바이트) | MD5 | SHA-256 |
|---|---|---|---|
| Inazuma Eleven 3 - Sekai e no Chousen!! - The Ogre (Japan).nds | 536,870,912 | de2690e8035a695bb65334599affeb7c | 1429c7b99ca8e7a18c49b6c2a9f61d43314b771c2c9a34c1e555bb0566c4cfe0 |
| Inazuma Eleven 3 - Sekai e no Chousen!! - Spark (Japan).nds | 536,870,912 | 0a68100507070cdfdd8258e780ba412f | 3417618e5f547deed932e9aad8ca2307da2c7ad8166077a799210d16cbe61232 |
| Inazuma Eleven 3 - Sekai e no Chousen!! - Bomber (Japan).nds | 536,870,912 | 97e17cce95c6d26157c642ffc46e401f | 57706dccf770356d13d42e374fd7b1f0c9212a53960729145bacf8165c97ec1f |

원본 SHA-1:

- 디 오우거 `BOEJ`: `9380f1d7ee75e7c6ef24f1b76c88ecdc85088957`
- 스파크 `BE8J`: `b19ccf3d9621af390f677da4af8be0fc5b29d609`
- 봄버 `BEZJ`: `3360a00373742f5611161e13c05579b11ebc0f07`

## 패치 결과

| 파일 | 크기(바이트) | SHA-256 |
|---|---|---|
| InazumaEleven3-Ogre-KO-v1.0.5.nds | 536,870,912 | 2e38f1403376da900a6e33e94faf114e8370c83d94b0ba3257042fa24dd2576b |
| InazumaEleven3-Spark-KO-v1.0.5.nds | 536,870,912 | 51d1bbebe7f34151c452542d206ee9053fea4cdc83e5790e6f64d8c73787f886 |
| InazumaEleven3-Bomber-KO-v1.0.5.nds | 536,870,912 | b771ba7ac400a55266569a24cbedd96ce7c10b54ceede37a447bb1e4fd482780 |

결과 SHA-1:

- InazumaEleven3-Ogre-KO-v1.0.5.nds: `0b9961a36ebbca3a7652a784c40604a13e8f2312`
- InazumaEleven3-Spark-KO-v1.0.5.nds: `165c9866472656309da71f4222d3a0dd1c9b3b46`
- InazumaEleven3-Bomber-KO-v1.0.5.nds: `758edbf04bd71b79ebc648ba7ffbe530a7bd1e4f`

## 배포 파일

| 파일 | 크기(바이트) | SHA-256 |
|---|---|---|
| InazumaEleven3-Ogre-KO-v1.0.5.zip | 8,788,744 | 96efbea4aea8756445205ad3b0a8464b2e87a2fabb51249f3208a476bb31883d |
| InazumaEleven3-Spark-KO-v1.0.5.zip | 7,570,732 | 548fdf89cc178aeac90d4d3af0dcf55dd8877beab28c2c350ac35abc69d61fcf |
| InazumaEleven3-Bomber-KO-v1.0.5.zip | 7,510,743 | f32cab6dd30a48a095ced3918c818c045181efb48a161836db87ef45e58fde74 |
| InazumaEleven3-Ogre-KO-v1.0.5.bps | 10,119,975 | 2b957aec2e813f95d118a99f1ea4bd2b6beb2649e19550e0d4a8ff6e0eefc51b |
| InazumaEleven3-Spark-KO-v1.0.5.bps | 8,792,434 | b8d1cea267f2ae190b0273f1c9801b2cae6baec343115418a51719fafa633247 |
| InazumaEleven3-Bomber-KO-v1.0.5.bps | 8,734,533 | 645dda62de650de365b0f29b0d0e24fe492b3b27a4f3c018b719caf8e95beff7 |

ZIP에는 BPS 패치, 적용 스크립트(apply_patch.py, bps.py), 설명서(README.txt), manifest.json, 사용한 글꼴 6종의 라이선스가 들어 있습니다. 내려받은 파일은 SHA256SUMS.txt로 확인할 수 있습니다.

## 추가 기능

번역 외에 새로 넣은 기능입니다. 일본 서비스가 끝났거나 다른 판이 있어야 얻을 수 있던 요소를 통신 없이 혼자 얻을 수 있게 했습니다. 해금 데이터는 원래 ROM 안에 있던 것입니다.

### 세 판 공통

- **암호를 게임 안에서 알기:** 일본판에서 잡지나 웹으로 공개하던 NPC 암호를 한글 정답으로 바꾸고, 해당 NPC가 대사에서 정답을 알려 주게 했습니다. 묻는 NPC가 없는 디 오우거의 극장판 암호는 입력 화면에 정답을 적었습니다.
- **배포 받기:** 통신 → 다운로드의 「Wi-Fi로 다운로드」나 「무선으로 다운로드」를 고르면 실제 통신 없이 배포 전체를 한 번에 받습니다. 배포 선수 60명(Wi-Fi 52명, 무선 8명)과 배포 아이템(디 오우거 19종, 스파크·봄버 20종)이며 블로그 알림도 생깁니다. 받은 뒤 저장을 고르고 이어하기로 불러와야 반영되며, 저장하지 않으면 남지 않습니다. 아이템은 상점에서 원래 가격으로 사고, 선수는 원래 방법으로 영입합니다.
- **프리미엄 스카우트·아이템:** 통신 → 다운로드의 「2→3 슈퍼 링크」에서 스카우트와 아이템을 통신 없이 고릅니다. 디 오우거는 「오우거 프리미엄 링크」도 같습니다. 원래 상대 게임의 팀을 보던 조건은 껐습니다. 스토리가 어느 정도 진행된 세이브에서 열립니다.
- **휴대폰 연동:** 옵션의 「휴대폰 연동」에서 아무 글자나 8자를 입력하면, 아직 없는 연동 선수 190명을 차례로 불러옵니다. 공식 사이트에서 받던 암호가 필요 없습니다. 옵션 메뉴는 원래처럼 스토리가 어느 정도 진행된 세이브에서 열립니다.
- **극장판 연동:** 스토리를 클리어한 뒤 옵션의 극장판 연동에서 어떤 답을 넣어도 통과합니다. 선수 2명과 비전서 1권을 받을 수 있습니다.

### 디 오우거

- **스파크·봄버 전용 선수:** 트레이드로만 얻던 49명을 오우거 프리미엄 스카우트 목록에 넣었습니다. 내줄 선수나 우정 포인트는 필요 없고, 합류 레벨은 기본값입니다.

### 스파크·봄버

- **시크릿:** 자기 판의 라이벌을 이긴 뒤 통신 메뉴의 시크릿에서 다른 판 없이 해금합니다.
- **다른 판 전용 팀:** 다른 판의 필드 조우 경기를 합쳤습니다. 자기 판의 조우에서 만나지 못하던 선수 스파크 87명, 봄버 88명을 만날 수 있습니다.
- 판 전용 아이템은 열지 않았습니다.
