일본어 학습 앱 PWA iOS/iPadOS 버전

구성 파일:
- index.html : 앱 본체
- manifest.json : 앱 이름/아이콘/설치 설정
- service-worker.js : 오프라인 캐시 설정
- icon-192.png / icon-512.png : 홈 화면 아이콘

아이폰/아이패드 사용 방법:
1. ZIP 압축을 풉니다.
2. 폴더 안 파일들을 HTTPS가 되는 곳에 올립니다.
   예: GitHub Pages, Netlify, Vercel
3. iPhone/iPad에서 Safari로 그 주소를 엽니다.
4. 공유 버튼 → 홈 화면에 추가
5. 홈 화면 아이콘으로 실행합니다.

중요:
- iOS는 로컬 HTML 파일만으로는 PWA 설치가 제한될 수 있습니다.
- Safari + HTTPS 주소로 여는 방식이 가장 안정적입니다.
