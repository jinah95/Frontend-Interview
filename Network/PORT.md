## 📶 PORT

### 📍 PORT 개념

포트는 한 서버에 여러 요청을 할 때 각 각의 출입문을 만들어주는 개념이라 생각하면 됩니다. <br /><br />
<img src="https://user-images.githubusercontent.com/97212459/183561656-046026c5-6703-4071-992d-cbde3dbd3dfc.PNG" width="500" height="320"><br />
[이미지 출처](https://velog.io/@nellholic108/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-OSI-7-%EA%B3%84%EC%B8%B5)<br />
IP에서 프로그램 구분이 안 된다는 얘기를 했었는데요. 동시에 게임, 웹툰, 보이스톡을 한다고 했을 때, 서버의 경우 요청들이 동시에 이루어지므로 구분이 필요합니다. <BR />
이때, 포트번호를 부여해주면 해당 데이터는 해당 포트로만 통신이 되는 방식이며, 포트 번호 정보는 TCP에 기록 되어 전송 됩니다.

<br />
** HTTP나 HTTPS 에 해당하는 포트가 정해져 있는데 용도에 따라 포트번호를 저장하는 것이 가능한지 아래에서 알아 봅시다. <br /> 포트번호를 지정하는 건 개발자가 지정합니다.<br />별도의 지정이 없다면 HTTP는 80, HTTPS는 443 포트로 기본 디폴트값이 배정됩니다.

### 🧿 PORT 번호

-   0 ~ 1023 : 잘 알려진 포트로 사용하지 않는 것이 좋습니다.
-   FTP : 20,21
-   TELNET : 23
-   HTTP : 80
-   HTTPS : 443<br /><br />
-   1024 ~ 65535 : 할당 가능 ✔

### 🔗 참고 출처

[velog](https://velog.io/@nellholic108/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%EA%B0%9C%EB%85%90-%EC%A0%95%EB%A6%AC#%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-%EA%B8%B0%EB%B3%B8-%EA%B0%9C%EB%85%90)
