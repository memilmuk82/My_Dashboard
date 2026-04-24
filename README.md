# WSL2 기반 동적 기술 배지 대시보드

## 입력 기능
- 입력창에 기술명을 입력하고 전송하면 리스트에 저장
- 전송 후 페이지는 redirect("/")로 새로고침

## 출력 기능
- 리스트에 저장된 데이터를 화면에 반복 출력
- 조건부 출력 (if / elif)
### 입력값에 따라 아래 규칙 적용
- python → [backend] python (회색)
-  sql → [DB] sql (보라색)
- html → html (주황색)
- bash → bash (초록색)
- 그 외 → [ETC] 입력값 (검정색)

## 실행 방법
```bash
python3 app.py
```