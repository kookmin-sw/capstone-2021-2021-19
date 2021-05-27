## Welcome to 19 Team GitHub Pages
실제 코드 작성 깃 주소 : https://github.com/sheayun-kmu/capstone-fadu-2021 </br>
팀페이지 주소 : https://kookmin-sw-github.io/capstone-2021-19 </br>

목차 
- [프로젝트 소개](#프로젝트-소개)
- [시연 영상](#시연-영상)
- [개발](#개발)


### 프로젝트 소개
개발자를 위한 코드 스타일, analysis status reporter plugin

한 눈에 알아보기 쉬운 코드! 클린한 코드!
필요한 코드! 예외처리가 잘 된 코드!
그러한 코드를 위해 작성한 코드를 분석하여 더욱 쉽고 간편하게 보여주기 위해 만드는 플러그인
팀장이 말하지 않아도 스스로 알 수 있다! 빠밤!
### 시연 영상
시연 영상 <br>
  [![Video Label](https://img.youtube.com/vi/LJM9ZKbF-mg/0.jpg)](https://youtu.be/LJM9ZKbF-mg) </br>
  
### 개발
### Static Analysis Status  

[Ikos](https://github.com/NASA-SW-VnV/ikos) 를 이용하여 코드를 분석해 나온 결과를 json으로 변경해주는 translator를 만든다.  
translator의 결과를 보여주는 파서를 작성한다. 해당 파서가 보여주는 결과와 해당 결과를 가시적으로 표현하는 대시보드를 작성해서 플러그인으로 빌드한다.  

### Code Styling Status  

[Clang-Format](https://clang.llvm.org/docs/ClangFormat.html) 을 이용하여 코드를 분석해 나온 결과를 xml으로 변경해주는 translator를 만든다.  
translator의 결과를 보여주는 파서를 작성한다. 해당 파서가 보여주는 결과와 해당 결과를 가시적으로 표현하는 대시보드를 작성해서 플러그인으로 빌드한다.  
