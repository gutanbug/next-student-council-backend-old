# next-student-council-backend-old
완전히 새롭게 개편된 총학생회 홈페이지입니다.

Backend 코드 : 기존에 있던 총학생회 코드를 복사해옴

CI 구축 : dev_deploy , main 브랜치에 올라갈 때 자동으로 CI가 되게끔 구축

CD 구축 : dev_deploy에 푸쉬할 경우 조건에 따라 CD가 되게끔 설정<br>
<li> EveryUniv/레포 가 아닐 경우
      <ul> CD 작업을 스킵함 </ul>
</li>
<li>EveryUniv/레포 일 시
      <ul> CD 작업을 진행하여 무중단 배포를 통해 도커에서 실행됨</ul>
</li>
