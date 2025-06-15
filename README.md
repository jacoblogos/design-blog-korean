# 한국 디자인 블로그 (Korean Design Blog)

> 한국어로 제작된 모던 디자인 블로그 웹사이트 - Jago Desain과 유사한 스타일

[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6.3-blue.svg)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC.svg)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-6.3.5-646CFF.svg)](https://vitejs.dev/)

## 🌟 주요 기능 (Features)

- **반응형 디자인**: 모든 디바이스에서 완벽한 사용자 경험
- **검색 기능**: 블로그 포스트를 쉽게 찾을 수 있는 실시간 검색
- **카테고리 필터링**: 디자인 튜토리얼, CSS, Freebies, 그래픽 디자인, 웹 개발, 템플릿 등
- **북마크 기능**: 관심 있는 포스트를 저장하고 관리
- **모던 UI**: 깔끔하고 직관적인 사용자 인터페이스
- **Korean Content**: 한국어로 제작된 디자인 관련 콘텐츠

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend**: React 18.3.1 + TypeScript
- **Styling**: Tailwind CSS 3.4.17
- **Build Tool**: Vite 6.3.5
- **Icons**: Lucide React
- **Code Quality**: Biome (ESLint + Prettier)
- **Package Manager**: Bun

## 🚀 시작하기 (Getting Started)

### 설치 및 실행 (Installation)

1. **저장소 클론**
   ```bash
   git clone https://github.com/jacoblogos/design-blog-korean.git
   cd design-blog-korean
   ```

2. **의존성 설치**
   ```bash
   bun install
   ```

3. **개발 서버 실행**
   ```bash
   bun dev
   ```

4. **브라우저에서 확인**
   ```
   http://localhost:5173
   ```

## 📁 프로젝트 구조

```
design-blog-korean/
├── src/
│   ├── App.tsx            # 메인 애플리케이션 컴포넌트
│   ├── main.tsx           # 애플리케이션 진입점
│   └── index.css          # 글로벌 스타일
├── package.json           # 의존성 및 스크립트
├── tailwind.config.js     # Tailwind CSS 설정
└── vite.config.ts         # Vite 설정
```

## 🎨 카테고리 (Categories)

- 디자인 튜토리얼 (Design Tutorials)
- CSS
- Freebies
- 그래픽 디자인 (Graphic Design)
- 웹 개발 (Web Development)
- 템플릿 (Templates)

## 🌐 배포 (Deployment)

이 프로젝트는 Netlify에 최적화되어 있습니다:

- Build command: `bun run build`
- Publish directory: `dist`

## 📝 라이선스 (License)

MIT License