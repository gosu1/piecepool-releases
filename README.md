# PiecePool

넣어 둔 노트와 자료를 AI가 읽고, 근거가 붙은 위키로 정리해 주는 노트앱이에요.

**최신 버전 0.3.0** · 2026-10-03 · [바뀐 점 보기](https://github.com/gosu1/piecepool-releases/releases/latest)

## 주요 기능

- **정리하기**: 노트와 PDF, 대화를 넣으면 AI가 주제별 위키 페이지로 정리해요. 위키의 기록 한 줄마다 근거가 된 원문이 붙어요.
- **내 위키 위에서 대화**: 물어보면 AI가 내 위키를 찾아 읽고 답해요. 대화창의 「정리하기」를 누르면 그 대화도 위키에 들어가요.
- **다른 AI에서 가져오기**: Claude, ChatGPT 같은 다른 AI와 나눈 대화를 가져와 위키로 정리해요.
- **그래프와 점검**: 위키 페이지가 어떻게 이어지는지 3D 그래프로 보고, 끊긴 근거와 링크를 점검해요.
- **되돌리기**: 정리할 때마다 기록이 남아서, 마음에 들지 않으면 예전 상태로 되돌릴 수 있어요.
- **내 기록은 내 컴퓨터에**: 노트와 위키, 대화는 마크다운 파일로 남아요. 앱을 지워도 그대로예요.

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
