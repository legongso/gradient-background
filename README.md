# 예배 그래디언트 루프 배경

예배용 그래디언트 루프 배경 (빠른 곡 · 중간 템포 · 느린 곡).

## 조작
| 키 | 동작 |
|---|---|
| `1` / `2` / `3` | 빠른(밝게) / 중간 / 느린(어둡게) 전환 |
| `F` | 전체화면 |
| `H` | UI·커서 숨김/표시 |

## 배포 (GitHub → Netlify)
1. GitHub에서 새 repo 생성 후 이 폴더를 push
   ```bash
   git init
   git add .
   git commit -m "init: worship gradient loops"
   git branch -M main
   git remote add origin https://github.com/<USERNAME>/<REPO>.git
   git push -u origin main
   ```
2. Netlify → **Add new site → Import an existing project → GitHub** → repo 선택
3. Build command: 비워둠 / Publish directory: `.` (netlify.toml에 이미 설정됨) → **Deploy**
4. 이후 `git push` 할 때마다 자동 재배포
