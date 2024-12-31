Discord에 Webhook을 이용하여 PR이나 Issue에 대한 알림을 전송.
Github의 Webhook기능을 이용하는 것 보다 action을 이용.
  - GitHub의 기본 Webhook 기능은 단순히 이벤트 발생 알림을 제공하지만, action을 이용하여 URL, title, description등의 요소를 설정해서 메시지로 보내 한번에 확인이 가능<br>
![image](https://github.com/user-attachments/assets/676a7f58-9ef2-4e04-8db0-d0b7ebdab79c)

post로 메시지를 보내는 것이기 때문에, 서버측에서 웹훅을 설정해서 알림을 받을 수 있음.(고객센터에 문의를 남긴다던지.)
