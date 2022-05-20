
## -목차-
&nbsp;&nbsp;1.  프로그램 소개
<br>
&nbsp;&nbsp;2.  사용한 기술스택 목록
<br>
&nbsp;&nbsp;3.  FRONTEND ARCHITECTURE
<br>
&nbsp;&nbsp;4.  BACKEND ARCHITECTURE
<br>
&nbsp;&nbsp;5   개발 과정
<br>
&nbsp;&nbsp;5   배포 링크
<br>
&nbsp;&nbsp;6   시연
<br>
&nbsp;&nbsp;7   Q&A
<br>
### 1. 프로그램 소개
요즘 밀레니엄 세대뿐만 아니라 MZ세대의 취미로 까지 떠오른 등산.<br/>
등산을 처음접하는 사람들에게 등산에 대한 정보를 제공하고 등산로에 대한 리뷰까지 작성할수 있게 해주는 사이트입니다.

### 2. 사용한 기술스택 목록
FRONT END<br/>
<img src="https://img.shields.io/badge/Vue.js-007396?style=for-the-badge&logo=vuedotjs&logoColor=white">
<img src="https://img.shields.io/badge/TypeScript-4479A1?style=for-the-badge&logo=TypeScript&logoColor=white">
<img src="https://img.shields.io/badge/Chart.js-6DB33F?style=for-the-badge&logo=Chart.js&logoColor=white">
<br/>
<img src="https://img.shields.io/badge/Axios-007396?style=for-the-badge&logo=Axios&logoColor=white">
<img src="https://img.shields.io/badge/Quasar-6DB33F?style=for-the-badge&logo=Quasar&logoColor=white">
<img src="https://img.shields.io/badge/Pinia-231F20?style=for-the-badge&logo=Pinia&logoColor=white">  
<img src="https://img.shields.io/badge/AWS-007396?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Git-4479A1?style=for-the-badge&logo=Git&logoColor=white">

BACK END<br/>
API 게이트웨이 도메인  
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Cloud GateWay-6DB33F?style=for-the-badge&logo=Spring Cloud GateWay&logoColor=white">  
<img src="https://img.shields.io/badge/AWS-007396?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Git-4479A1?style=for-the-badge&logo=Git&logoColor=white">

유저 도메인<br/>
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
<img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=Apache Kafka&logoColor=white">  
<img src="https://img.shields.io/badge/MySQL-007396?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/Spring Web Flux-6DB33F?style=for-the-badge&logo=Spring Web Flux&logoColor=white">
<img src="https://img.shields.io/badge/R2DBC-231F20?style=for-the-badge&logo=R2DBC&logoColor=white">
<img src="https://img.shields.io/badge/JWT-231F20?style=for-the-badge&logo=JWT&logoColor=white">  
<img src="https://img.shields.io/badge/AWS-007396?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Git-4479A1?style=for-the-badge&logo=Git&logoColor=white">
****
산 도메인  <br/>
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
<img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=Apache Kafka&logoColor=white">  
<img src="https://img.shields.io/badge/MySQL-007396?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/Spring Web Flux-6DB33F?style=for-the-badge&logo=Spring Web Flux&logoColor=white">
<img src="https://img.shields.io/badge/R2DBC-231F20?style=for-the-badge&logo=R2DBC&logoColor=white">
<img src="https://img.shields.io/badge/AWS-007396?style=for-the-badge&logo=amazonaws&logoColor=white">
<img src="https://img.shields.io/badge/Git-4479A1?style=for-the-badge&logo=Git&logoColor=white">

### 3. FRONTEND ARCHITECTURE
![image](https://user-images.githubusercontent.com/31757314/169457228-d5216ea7-0dc3-4820-99b6-d17e517c1472.png)

### 4. BACKEND ARCHITECTURE
![image](https://user-images.githubusercontent.com/31757314/169458471-d49c116f-3c2c-4c94-a098-0e932e839189.png)


### 5 개발 과정
1. 구현 항목 및 API
- User    : 유저가 로그인을 시도한다.
- User    : 유저가 회원가입을 시도한다.
- Moutain : 유저가 산 리스트를 조회한다.
- Moutain : 유저가 특정산을 조회한다.
- Moutain : 유저가 특정산을 즐겨찾기를 조회한다.
- Moutain : 유저가 특정산의 리뷰를 불러온다.
- Moutain : 유저가 특정산의 리뷰를 작성한다.
- Moutain : 유저가 특정산의 리뷰를 삭제한다.
- Moutain : 유저가 특정산의 리뷰를 추천한다.
- Moutain : 유저가 특정산의 즐겨찾기를 추천한다.
- Moutain : 유저가 특정산의 즐겨찾기를 해제한다.
- Moutain : 유저가 특정산 리뷰를 등록할때 이미지를 첨부한다.
- User    : 유저가 마이페이지에서 내 정보를 조회한다.
- User    : 유저가 마이페이지에서 내 뱃지를 조회한다.
- User    : 유저가 마이페이지에서 회원탈퇴한다.
- User    : 유저가 마이페이지에서 즐겨찾기한 산목록을 불러온다.
- User    : 유저가 마이페이지에서 작성한 리뷰 목록을 불러온다.<br/>
[API 목록 정의서 바로가기](https://www.notion.so/Holam-41cd098b37c0496f86d296960f333df3)
2. [팀협업규칙](https://github.com/hola-mountain/back/wiki/%ED%8C%80-%ED%98%91%EC%97%85-%EA%B7%9C%EC%B9%99)<br/>
3. [마일스톤 Back](https://github.com/hola-mountain/back/milestones), [마일스톤 Front](https://github.com/hola-mountain/front/milestones)<br/>
4. [프로토타이핑](https://ovenapp.io/view/mVyNHivUTx5M0n7dOR2q59s3rk5NFNAu/)<br/>
5. [ERD Cloud](https://www.erdcloud.com/d/E9duAnHgfLZhhrRFd)
6. 카카오톡<br/>
![image](https://user-images.githubusercontent.com/31757314/169469223-6f2a80fb-3f1b-49df-b224-fa5b9da4b4ea.png)
![image](https://user-images.githubusercontent.com/31757314/169469285-6d6410e7-e605-459a-96fd-d6bcb90992df.png)
7. [에러공유](https://github.com/hola-mountain/back/wiki/%EC%97%90%EB%9F%AC-%EA%B3%B5%EC%9C%A0)<br/>

### 6 배포 링크
[홀람 바로가기](http://holam-front-s3.s3-website.ap-northeast-2.amazonaws.com)
![image](https://user-images.githubusercontent.com/31757314/169456865-1aeb500d-b093-42ac-ba1a-3cc1c513c149.png)

# Collaborators
<table>
    <tr>
        <td align="center">
            <a href="https://github.com/LeeJams"><img  width="100px" src="https://avatars.githubusercontent.com/u/89899636?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/diqksrk"><img  width="100px" src="https://avatars.githubusercontent.com/u/31757314?v=4" /></a>
        </td>
        <td align="center">
            <a href="https://github.com/seonghoJoo"><img  width="100px" src="https://avatars.githubusercontent.com/u/32606456?v=4" /></a>
        </td>
    </tr>
    <tr>
        <td align="center">이재민 - Front</td>
        <td align="center">강민준 - Back</td>
        <td align="center">주성호 - Back</td>
  </tr>
    <tr>
        <td align="center">Total Page</td>
        <td align="center">USER DOMAIN, MYPAGE, API GATEWAY, INFRA STRUCTURE, KAFKA</td>
        <td align="center">MOUNTAIN DOMAIN, KAFKA</td>
    </tr>
</table>
