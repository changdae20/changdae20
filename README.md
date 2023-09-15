# 안녕하세요 👋🏻

저의 깃헙을 찾아주셔서 감사합니다.<br/>
항상 성장하는 개발자가 되고, 재미있는 것들을 많이 보여드리도록 노력하겠습니다.<br/><br/>
**저에 대한 간단한 설명은 여기서 찾아보실 수 있습니다 : [CV](CV_ChangdaeSon.pdf)**
<br/><br/>

# Problem Solving 🏹
[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=changdae20)](https://solved.ac/changdae20) <br/><br/>
PS에 사용한 소스코드들은 여기서 보실 수 있습니다 : [BOJ](https://github.com/changdae20/BOJ)
<br>
# 자기소개 🙃
* 2021.03.25 ~ 2023.02.24 산업기능요원(보충역) 복무만료(마크애니)
* 2021.07.12 ~ 2023.09.22 (주)마크애니
* 2018.03.01 ~    현재    서울대학교 전기정보공학부 재학중 (현재 121/130학점 이수, GPA 3.92/4.3)
* 2016.03.01 ~ 2018.02.28 울산과학고등학교 조기졸업(2학년 졸업)<br/><br/>

# 진행한 프로젝트 🔧

<img src="https://user-images.githubusercontent.com/46400212/225736713-87af4a77-a0a9-4efd-8f40-7fbd4a2fcc26.png" style="height:200px">

[LabPPBot](https://github.com/changdae20/LabPPBot_Cpp) 이라는 프로젝트를 혼자서 진행하고 있습니다 <br/>
여기서 사용되는 REST API 서버는 [LabPPBot_Server](https://github.com/changdae20/LabPPBot_Server)에서 확인하실 수 있습니다. <br/>

**LabPPBot은 C++로 구현한 자동 카카오톡 봇**으로, 일반 카카오톡 봇인 플러스친구등과는 자유롭게 단톡방에 초대하여 친구들과 함께 사용할 수 있다는 점이 다릅니다. <br/>
현재는 게임 정보 로딩, 자동 업데이트, 오늘의 백준, 백준 알리미 등, 재미를 위한 가챠기능 등의 다양한 기능이 구현되어 있습니다. <br/>

<img src="https://github.com/changdae20/changdae20/assets/46400212/9eaabc9b-52fa-4fc2-93f2-44c7fb14b9d6">

현재 제가 가장 많이 열정, 애정을 쏟는 프로젝트입니다.
<br/>

<hr/>
"지능시스템개론"이란 과목을 수강하며 자율주행 자동차를 만든 프로젝트입니다. 사용한 주요 알고리즘으로는 다음과 같은 것들이 있습니다 : <br/>
<br/>PID제어(설정한 경로대로 차를 잘 움직이도록 제어)
<br/>RRT(지도와 로봇의 위치가 주어졌을 때 경로를 탐색하고 설정)
<br/>AMCL(지도와 센서를 통해 얻은 데이터를 종합하여 위치를 결정)
<br/>SLAM(로봇의 위치를 결정하고 지속적으로 지도를 작성)
<br/><br/>Ubuntu 18.04환경에서 ROS를 이용하여 작업했고, C++언어로 개발했습니다. 학교 건물 301동 제1공학관 1층에서 실제 RC car를 이용하여 프로젝트를 진행하여 1등이라는 좋은 성적을 거두었습니다🥇<br/><br/>

훌륭하신 조교님들이 촬영해주신 영상들이 남아있습니다📹
<br/>[Repository](https://github.com/changdae20/Introduction-to-Intelligent-System)
<br/>[1인칭 영상](https://youtu.be/qmPlMQ_SL7M)
<br/>[고정시점 영상](https://youtu.be/16EdMgwOFfY)
<br/>[프로젝트 설명](http://rllab.snu.ac.kr/courses/intelligent-systems_2020/project-information)

<hr/>
"임의 정밀도 부동소수점을 이용한 딥러닝 모델 양자화 및 성능 손실 연구"라는 주제로 학부 졸업연구를 진행하고 있습니다.
<br/>
FP32, FP16, FP8처럼 bitwidth를 줄일 수록 추론이 빨라지고 모델의 용량이 작아지는 반면 성능 손실 가능성이 커진다는 점에 착안하여 8,16,32비트가 아닌 사용자가 지정하는 임의 정밀도 부동소수점을 이용하여 모델을 양자화하는 프레임워크를 개발하였습니다.<br/>
Pytorch의 공식 구현 코드를 일부 참고하여 C++로 작성하였습니다.<br/>

<img src="https://github.com/changdae20/changdae20/assets/46400212/d7860966-f398-45ef-83e7-427566659887">

```
root@1723a04c0176:~/qresnet# ./bin/main 
[util.hpp L24] image.rows : 128, image.cols : 128
Current Precision : total 15-bit
=== Predicted Result ===
Top 1 : tiger, Panthera tigris with logit 41.00000000000000000000
Top 2 : tiger cat with logit 34.37500000000000000000
Top 3 : jaguar, panther, Panthera onca, Felis onca with logit 29.09375000000000000000
Top 4 : leopard, Panthera pardus with logit 26.48437500000000000000
Top 5 : snow leopard, ounce, Panthera uncia with logit 25.06250000000000000000
Elapsed time : 4362ms
```

[Repository](https://github.com/changdae20/qResNet)

# Contact? 📞

마지막까지 읽어주셔서 정말 감사드립니다. 혹시 저에대해 추가적으로 궁금한 점이 있으시다면, 아래 이메일로 연락주시면 감사하겠습니다! 블로그에는 저의 개인적인 일상이나 개발 일기등이 있으니, 제 이야기가 더 궁금하시다면 찾아와 소통해주시면 정말 감사할 것 같습니다.<br/><br/>
E-Mail : changdae20@naver.com <br/>
Blog : [창대는 공대공대 :: 네이버 블로그](https://blog.naver.com/changdae20)
