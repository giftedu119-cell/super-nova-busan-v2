# SUPER 노바

관광객과 부산 수산시장 이용자가 실시간 수산물 시세를 확인하고, 가격을 비교해 바가지 거래를 피할 수 있도록 돕는 웹 서비스입니다.

## 주요 기능

- 수산물 종류별 시세와 최근 1년 가격 변동
- 최근 1년 평균가 기준 AI 가격 분석
- 바가지 안 씌우기 인증 점포 86곳 비교
- 구매 후기, 영수증 등록 화면, 소비자 커뮤니티
- 별점순·주문량순 점포 정렬과 최저가 표시

## 공개 사이트

- GitHub Pages: <https://giftedu119-cell.github.io/super-nova-busan-v2/>
- ChatGPT Sites: <https://super-nova-busan.yeonhui-lim-5750.chatgpt.site/>

## 개발

Node.js 22 이상이 필요합니다.

```bash
npm install
npm run dev
```

GitHub Pages용 정적 빌드는 다음 명령으로 확인할 수 있습니다.

```bash
npm run build:pages
```

현재 GitHub Pages는 `main` 브랜치 루트의 정적 배포 파일을 사용합니다. 전체 개발 소스는 저장소의 `super-nova-source.zip`에서도 내려받을 수 있습니다.
