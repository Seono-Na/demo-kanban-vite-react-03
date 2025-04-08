---
## 📝 Demo Kanban

칸반보드 기능을 중심으로 한 Vite + React + TypeScript 프로젝트입니다.

최신 프론트엔드 기술 스택을 기반으로 구조화되고 확장 가능한 형태로 구성되어 있습니다.

---

### 📦 사용 스택

- **Vite** + **React 19** + **TypeScript**
- **SWC** 기반 빌드
- **Tailwind CSS v4** + **shadcn/ui**
- **pnpm** 패키지 매니저
- **ESLint**, **Prettier**, **Husky**, **Commitlint**

---

### ⚙️ 설치 및 실행 방법

1. **pnpm 설정**  
   이 프로젝트는 `pnpm@9.12.3`을 사용합니다.

   ```
   corepack enable
   corepack prepare pnpm@9.12.3 --activate
   ```

2. **레포 클론 및 의존성 설치**

   ```
   git clone git@github.com:Seono-Na/demo-kanban-vite-react-03.git
   cd nettee-kanban
   pnpm install
   ```

3. **개발 서버 실행**

   ```
   pnpm dev
   ```

4. **빌드**

   ```
   pnpm build
   ```

5. **Lint & Format**

   ```
   pnpm lint         # ESLint 실행
   pnpm format       # Prettier 실행
   ```

---

### 🧪 스크립트 목록

| 명령어         | 설명                          |
| -------------- | ----------------------------- |
| `pnpm dev`     | 개발 서버 실행 (Vite)         |
| `pnpm build`   | 타입 체크 후 빌드             |
| `pnpm preview` | 빌드된 앱을 로컬에서 미리보기 |
| `pnpm lint`    | ESLint 실행                   |
| `pnpm format`  | Prettier로 코드 포맷팅        |
| `pnpm prepare` | Husky 초기화용                |

---

### ✅ 커밋 컨벤션

이 프로젝트는 명확한 변경 이력을 위해 다음과 같은 커밋 메시지 컨벤션을 따릅니다:

| 태그       | 설명                                   |
| ---------- | -------------------------------------- |
| `feat`     | 새로운 기능 추가                       |
| `fix`      | 버그 수정                              |
| `docs`     | 문서 변경 (README 등)                  |
| `style`    | 코드 스타일 변경 (포맷팅, 세미콜론 등) |
| `design`   | 사용자 UI 디자인 변경 (CSS 등)         |
| `test`     | 테스트 코드 추가/수정                  |
| `refactor` | 리팩토링 (기능 변경 없음)              |
| `build`    | 빌드 관련 변경                         |
| `ci`       | CI/CD 관련 변경                        |
| `perf`     | 성능 개선                              |
| `chore`    | 기타 변경 사항 (패키지 업데이트 등)    |
| `rename`   | 파일 혹은 폴더명을 수정한 경우         |
| `remove`   | 파일을 삭제한 경우                     |

`Husky`, `Commitlint`, `Lint-staged`가 설정되어 있으며, 커밋 전에 자동으로 lint 및 포맷팅이 수행됩니다.

---

### 📁 디렉토리 구조 (초기 기준)

```
src/
├─ shared/
│  └─ components/ui/  # shadcn/ui 구성요소
│  └─ lib/            # 유틸 함수들
├─ index.css          # 글로벌 스타일 설정
└─ main.tsx
```

---
