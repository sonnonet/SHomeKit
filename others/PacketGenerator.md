<h2>Packet Generator</h2>
<img src="https://raw.githubusercontent.com/sonnonet/SHomeKit/master/others/PacketGenerator.png">

<p>강정훈 책임님께서 요청하신 Packet Generator입니다.<br>
제가 예전에 만들었던 JAVA로 된 프로그램입니다.<br>
실행하실때는 Java 1.7이상을 설치하신후 "java -jar PacketGenerator.jar" 라고 입력하시면 실행이 됩니다.</p>

<p>위의 스크린샷은 제가 SESE 8282서버 테스트할때 했던 패킷 설정입니다.<br>
위와 같은 TinyOS Packet의 Base패킷을 위한 Library는 미리 정의 되어있어서 선택만 하시면 됩니다. </p>

<p>오른쪽 부분의 6. Target Server Configuration의 설정을 맞추고 Test를 누르고 Success가 떠야만 <br>
해당서버로 Packet이 보내집니다.</p>

<p>값은 그냥 숫자만 입력하면 10진수의 Integer가 정해진 Byte만큼 바뀌어서 보내집니다. <br>
앞에 0x를 붙이면 16진수의 Integer가 정해진 Byte만큼 바뀌어서 보내집니다.<br>
12.0처럼 소수로 입력하면 Float가 Byte로 바뀌어서 보내집니다.(테스트 부족) </p>
