# 원본 소스

최초 커밋 소스는 아래 주소로부터 fork한 내용입니다.   
(https://github.com/nomadcoders/nomad-movies.git)   

# 어플리케이션 실행 방법
1. expo를 install 합니다   
   (참고 : https://docs.expo.io/versions/latest/introduction/installation/)
   ```
   npm install -g expo-cli

   ```
2. 의존성있는 모듈들을 설치해줍니다.
   ```
   cd nobrary-mobile
   npm install
   ```
   
3. 프로젝트 폴더에서 expo start를 합니다.
   ```
   expo start
   ```

4. 모바일 기기에서 본 어플리케이션을 실행합니다
   - expo start가 완료되면 local web page가 실행됩니다 (보통 http://localhost:19000/)
   - 안드로이드 : 플레이스토어에서 [expo](https://play.google.com/store/apps/details?id=host.exp.exponent)를 설치합니다
   - expo 어플리케이션을 실행하여 웹 페이지 하단의 QR코드를 스캔합니다   
     (expo start를 수행한 local 컴퓨터와 모바일기기가 같은 wifi망에 있어야 합니다)
   - 스캔이 완료되면 자동으로 모바일 기기에서 본 어플리케이션이 실행됩니다.
   - 별도 설정을 건드리지 않으면 development mode로 실행되며,    
      Live Reload가 적용된 상태입니다.   
      메뉴버튼(뒤로가기 버튼을 long click)을 누르면 관련 메뉴가 팝업됩니다.   
      (참고 : https://docs.expo.io/versions/latest/workflow/development-mode)
