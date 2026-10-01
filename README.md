# PiecePool

대화할수록 나를 알게 되는 노트앱이에요. 예전에 한 말을 날짜와 원문 그대로 꺼내 놓고, 딱 하나만 되물어요.

**최신 버전 0.2.0** · 2026-10-01 · [바뀐 점 보기](https://github.com/gosu1/piecepool-releases/releases/latest)

## 주요 기능

- **인터뷰어**: 오늘 있었던 일을 적으면 들어주고, 한 번에 하나씩 되묻고, 예전에 한 말과 이어 줘요.
- **첫인상 카드와 나 리포트**: 상황 카드 14장에서 보기를 고르면 나 리포트가 나와요. 문장마다 근거가 된 내 답이 붙고, 세로 이미지 한 장으로 공유할 수 있어요.
- **말투 셋**: 솔직한 아리스토텔레스, 팩폭 T, 공감 F 중에 골라요.
- **사주 궁합**: 생년월일을 적으면 궁합을 물어볼 수 있어요. 간지는 앱이 계산하고, AI는 풀이만 해요.
- **내 기록은 내 컴퓨터에**: 노트와 대화는 마크다운 파일로 남아요. 앱을 지워도 그대로예요.

## 요구 사항

- 맥: M1 이후 애플 실리콘 맥
- 윈도우: 윈도우 10 이상 64비트
- AI 기능: 파일럿 동안은 메일로 받은 키를 앱의 「AI 켜기」에 넣어야 해요.

## 내려받기

- 맥: [PiecePool.dmg](https://github.com/gosu1/piecepool-releases/releases/latest/download/PiecePool.dmg)
- 윈도우: [PiecePool-Setup.exe](https://github.com/gosu1/piecepool-releases/releases/latest/download/PiecePool-Setup.exe)

## 설치 안내 (파일럿)

지금은 파일럿 판이라 운영체제의 개발자 인증을 받지 않았어요. 그래서 처음 설치할 때 경고가 한 번 떠요. 아래 순서대로 넘기면 돼요.

### 윈도우

1. [`PiecePool-Setup.exe`](https://github.com/gosu1/piecepool-releases/releases/latest/download/PiecePool-Setup.exe)를 받아요. 브라우저가 "일반적으로 다운로드되지 않는 파일"이라며 막으면, 다운로드 목록에서 「유지」를 눌러요.
2. 받은 파일을 열면 파란 "Windows의 PC 보호" 창이 떠요. 「추가 정보」를 누른 뒤 「실행」을 눌러요.
3. 설치는 저절로 끝나고, 바탕화면에 PiecePool 아이콘이 생겨요.

새 버전이 나오면 앱이 스스로 받아서 알려 드려요.

### 맥 (M1 이후 애플 실리콘 맥)

1. [`PiecePool.dmg`](https://github.com/gosu1/piecepool-releases/releases/latest/download/PiecePool.dmg)를 열고, PiecePool을 「응용 프로그램」 폴더로 끌어다 놓아요.
2. 처음 열면 "Apple은 'PiecePool'에 악성 코드가 없는지 확인할 수 없습니다"라는 창이 떠요. 「완료」를 눌러요. 「휴지통으로 이동」은 누르지 마세요.
3. 「시스템 설정」 → 「개인정보 보호 및 보안」으로 가서 아래로 내리면, "'PiecePool'이(가) Mac을 보호하기 위해 차단되었습니다"라는 문구 옆에 「그래도 열기」가 있어요. 눌러서 암호나 Touch ID로 확인한 뒤, 한 번 더 「그래도 열기」를 눌러요.
4. 그래도 열리지 않으면 「터미널」 앱에 아래 한 줄을 붙여 넣고 Enter를 눌러요.

   ```
   xattr -dr com.apple.quarantine /Applications/PiecePool.app
   ```

맥은 아직 자동 업데이트가 되지 않아요. 새 버전이 나오면 이 페이지에서 다시 받아 주세요.

## 참고

- 홈페이지: https://piecepool.pages.dev
- 문의: dxc1196@gmail.com
- 이 저장소에는 설치 파일과 업데이트만 올려요. 소스 코드는 공개하지 않아요.
