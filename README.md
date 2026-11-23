# Hi, I'm JongYun Jeong 👋

Frontend Developer

## About Me

브라우저 런타임의 성능 병목을 숫자로 해결하고, 사용자가 실제로 쓰는 프로덕트를 만드는 데 관심이 많은 프론트엔드 개발자 정종윤입니다.

## Tech Stack

- **Frontend:** React, Next.js, Vue.js, TypeScript, Vite, Tailwind CSS
- **State Management:** Recoil, Zustand, React Query, Redux  
- **Backend & DevOps:** Node.js, Nest.js, Docker, AWS, GitHub Actions  
- **Tools:** VSCode, Git, ESLint, Prettier, Vitest  

## Projects

### [이리와지지 (erwagg.com)](https://erwagg.com)
1.5만 동접 게임의 3인 조합 통계 분석 플랫폼 (1인 개발 실서비스)  
*Next.js 15, Nest.js, Supabase, TypeScript, Tailwind CSS, Vitest*
- **1인 개발 실서비스**: 마케팅 없이 오가닉으로 **최고 DAU 1,300** 달성
- **INP 80.9% 단축**: 롱태스크 분산 및 렌더링 스케줄링으로 **Lab INP p95 1,128ms ➔ 216ms** 개선
- **캐시 MISS 50.1%p 절감**: 공용 후보군 단위 캐시 키 재설계로 **운영 Data Cache MISS 72.5% ➔ 22.4%** 최적화

### [ReXume](https://github.com/ReXume/techeer-resume)
웹 기반 PDF 뷰어 및 이력서 피드백 플랫폼 (팀 프로젝트 / FE 3인)  
*React, TypeScript, PDF.js, Zustand, Tailwind CSS, Vitest*
- **Canvas 메모리 63.2% 절감**: 50페이지 렌더링 시 LRU 캐시 및 `canvas.width=0` 초기화로 **메모리 증가분 1.46GB ➔ 539MB** 통제
- **테스트 기반 CI**: 핵심 사용자 시나리오를 Vitest 명세로 고정하고 GitHub Actions 자동 검증 구축

### [QuickSplit](https://quick-split-delta.vercel.app/)
모임 총무를 위한 1인 완결형 정산 PWA
*Next.js 15, React 19, Gemini 2.5 Flash Vision, PWA, Tailwind CSS*
- **Gemini 비전 OCR 파이프라인**: 캔버스 사전 압축으로 Vercel 4.5MB 제한을 극복하고, OpenAPI 3.0 `responseSchema`로 1원 단위 데이터 무결성 보장
- **어필리에이트 뷰어빌리티 계측**: `IntersectionObserver` 기반으로 화면에 50% 이상 노출된 시점만 측정하는 유효 노출 및 전환율(CTR) 트래킹 파이프라인 구축

## Open Source Contributions

### Nuxt Ecosystem

Two merged contributions to the Nuxt ecosystem, focused on pnpm package resolution and module evaluation edge cases.

- **[nuxt/cli #1283](https://github.com/nuxt/cli/pull/1283)**  
  pnpm 11 global virtual store 환경에서 Nuxt CLI가 Vite package metadata를 찾지 못하는 문제를 수정했습니다.  
  Parent dependency 기반 package resolution을 구현했으며, maintainer의 범용화 작업을 거쳐 `@nuxt/cli` v3.35.0에 반영됐습니다.

- **[nuxt/content #3791](https://github.com/nuxt/content/pull/3791)**  
  Nuxt Content의 validator 탐색 실패를 package resolution과 duplicate module evaluation 문제로 나누어 분석했습니다.  
  Module-relative dependency resolution, shared validator context를 구현했으며, 프로젝트 convention에 맞춘 refinement 후 main에 병합됐습니다.

## Featured Articles
- [메인 스레드 교통정리: 1,060ms 롱태스크 분산과 INP 80.9% 개선기](https://medium.com/@whd3558/%EB%A9%94%EC%9D%B8-%EC%8A%A4%EB%A0%88%EB%93%9C-%EA%B5%90%ED%86%B5%EC%A0%95%EB%A6%AC%ED%95%98%EA%B8%B0-1de8da9302ad)
- [PDF.js 메모리 누수 개선기: Canvas backing store 초기화로 메모리 63.2% 절감](https://medium.com/@whd3558/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%84%B1%EB%8A%A5-%EC%B5%9C%EC%A0%81%ED%99%94-%EA%B2%BD%ED%97%98-pdf-%EB%A9%94%EB%AA%A8%EB%A6%AC-%EA%B0%9C%EC%84%A0%EA%B8%B0-0830661e9551)
- [TTL은 캐시 재사용을 보장하지 않는다: 비싼 MISS를 줄이는 캐시 키 설계](https://medium.com/@whd3558/7%EC%9D%BC%EC%A7%9C%EB%A6%AC-%EC%BA%90%EC%8B%9C%EA%B0%80-%ED%95%98%EB%A3%A8-%EB%A7%8C%EC%97%90-%EB%8B%A4%EC%8B%9C-miss%EA%B0%80-%EB%82%9C-%EC%9D%B4%EC%9C%A0-9038fe4dcaa2)
- [pnpm 11 global virtual store에서 Nuxt CLI 버전 배너가 깨진 이유](https://medium.com/@whd3558/pnpm-11-global-virtual-store%EC%97%90%EC%84%9C-nuxt-cli-%EB%B2%84%EC%A0%84-%EB%B0%B0%EB%84%88%EA%B0%80-%EA%B9%A8%EC%A7%84-%EC%9D%B4%EC%9C%A0-4b13a9f9ca59)
- 👉 [Medium에서 전체 기술 블로그 글 보기 ➔](https://medium.com/@whd3558)

## Contact

- 📧 jongyun.jeong.00@gmail.com  
- 🔗 [https://github.com/BellYun](https://github.com/BellYun)
