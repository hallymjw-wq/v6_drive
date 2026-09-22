V6 GPS Active Sound — iPhone/PWA

용도
- OBD 없이 iPhone GPS 속도를 읽어 가상 6단 기어와 가상 RPM을 계산합니다.
- 3.5L 자연흡기 60° V6 느낌의 엔진음을 Web Audio로 실시간 합성합니다.
- iPhone을 차량 CarPlay/Bluetooth 오디오에 연결하면 차량 스피커로 들을 수 있습니다.

중요
- GPS 위치정보는 HTTPS에서만 동작합니다.
- index.html을 '파일 앱에서 그냥 열기' 방식으로는 GPS 권한이 정상 작동하지 않을 수 있습니다.
- 정적 웹호스팅(GitHub Pages, Netlify, Cloudflare Pages 등)에 이 폴더 전체를 올려 HTTPS 주소로 접속하세요.
- 처음 START DRIVE를 누르면 위치정보 권한을 허용하세요.
- iOS 웹앱은 백그라운드에서 GPS/오디오가 중단될 수 있으므로 주행 중 화면을 켜두는 것을 권장합니다.

설치
1) 폴더 전체를 HTTPS 정적 호스팅에 업로드
2) iPhone Safari에서 해당 주소 열기
3) 공유 버튼 → 홈 화면에 추가
4) 차량 오디오(CarPlay 또는 Bluetooth)에 연결
5) V6 Drive 실행 → START DRIVE → 위치정보 허용

기능
- GPS 속도 표시
- 속도/가속도 기반 가상 스로틀
- 6단 자동 가상 변속
- 가상 RPM
- 3.5L NA 60° V6 실시간 합성
- 엔진음 크기 조절
- 변속 성향 조절
- DEMO 모드

주의
- 실제 엔진 RPM/기어를 읽지 않으므로 실제 차량 동작과 완전히 일치하지 않습니다.
- 운전 중 조작하지 말고, 출발 전에 실행/음량을 맞추세요.
