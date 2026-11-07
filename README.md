# Outlook_mail_Link_maker - 메일 링크 (Outlook 추가 기능)

선택한 메일로 바로 가는 웹 아웃룩 링크를 만들어 복사해 주는 추가 기능.
클래식 아웃룩 / 새 아웃룩 / 웹 아웃룩 모두 동작.

## 1. GitHub Pages에 올리기 (한 번만)
1. github.com 로그인 → New repository → 이름 `Outlook_mail_Link_maker`, **Public** 으로 생성
2. "uploading an existing file" 눌러서 이 폴더의 파일 전부 업로드
   - `taskpane.html`, `manifest.xml`, `README.md`, `assets` 폴더(아이콘 5개)
3. Settings → Pages → Branch: `main` / `/(root)` → Save
4. 1~2분 뒤 `https://hachi-fy.github.io/Outlook_mail_Link_maker/taskpane.html` 이 열리면 성공

## 2. manifest.xml 수정
- 메모장으로 열고 `hachi-fy` 를 본인 GitHub 아이디로 **모두 바꾸기** (Ctrl+H)
- 수정한 파일은 PC에 저장 (GitHub에 다시 올릴 필요는 없음)

## 3. 아웃룩에 설치
1. 크롬에서 aka.ms/olksideload
2. 내 추가 기능 → 사용자 지정 추가 기능 추가 → **파일에서 추가** → manifest.xml 선택
3. 경고창 나오면 설치

## 4. 사용
- 메일 열기 → 리본(또는 메일 위 `…`)에서 **메일 링크** 버튼
- 패널 오른쪽 위 **핀** 누르면 고정 → 메일 바꿀 때마다 자동 갱신
- **글자에 링크 걸어서 복사** → OneNote / Word / Excel / Teams에 Ctrl+V

## 참고
- 링크는 내 메일함 기준이라 나만 열림
- 메일을 다른 폴더로 옮기거나 삭제하면 링크가 깨질 수 있음 → 정리 끝난 다음 링크 만들기
- 코드 고친 뒤엔 GitHub에 taskpane.html만 다시 올리면 됨 (재설치 불필요)
