## webserver computing HW4
- django를 사용해, CSRF verification을 확인해보았다.
  1. templates 에 login.html, write.html, attack.html 을 생성
  2. views.py에서 @csrf_exempt를 사용하지 않고,http://127.0.0.1.8000/attack 접속시,<br>
     ### CSRF verification 인증 불가 <br>
     반대로 사용하면, http://127.0.0.1.8000/attack 접속시,<br> 
     ### CSRF verification 인증 가능
  3. http://127.0.0.1.8000/admin 에서의 Posts로 확인 가능
