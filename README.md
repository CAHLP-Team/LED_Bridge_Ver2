# <div align=center> Led_Bridge_project V2</div>
#### <div align=center> 본 프로젝트는 LED Bridge V1 프로젝트의 문제점 및 기능은 개선하고자 추진하게된 개인 토이 프로젝트입니다. </div>                             

* 이전 Ver1 제작 과정및 상세내용은 네이버 블로그에서 확인 하실수있습니다!
 <a href="https://blog.naver.com/nifskr/222656021598"> <img src="https://user-images.githubusercontent.com/92977647/151411167-b7a060a3-2830-4e4a-abaa-7b8e7bdc2a64.png" ></a><br>
 - V1 브릿지 [Nifskor] <a href="https://github.com/Nifskor/Led_Bridge_project" target="GitHub"><img src="https://img.shields.io/badge/GitHub-000000?style=flat-square&logo=GitHub&logoColor=white"/></a>
***
### 개발 팀원 
1. Nifskor
2. 
***
### 업그레이드 이유 
> 1. 약 반년정도 사용한 결과 프레임의 내구성 부실
> 2. 소프트웨어의 조작의 불편함 
> 3. 하드웨어 버튼 작동 인식 오류 
> 4. 사용하기에 다소 불편한 위치에 물리적 버튼이 위치해있음.
> 5. 기본 USB 충전기로 사용하기엔 문제가 있는점.

### 이번 업그레이드의 핵심 기능 
> 1. 라즈베리파이 제로 사용하여 웹으로 제어한다.
> 2. 하드웨어 출력 품질을 높인다.
> 3. 철사를 사용하여 힘을주어도 견딜수있는 내구성을 높인다.
> 4. 전원 제어부를 하나로 통일하여 사용해본다 ( 또는 고출력 충전기로 교체한다)

>* <font color ="red"> <b> 따라서 이번 업그레이드의 핵심은 (안전성, 편리성, 내구성, 품질) 을 잡는것이 목표이다. 
  
### 보다 높은 품질, 빠른 진행을 위해 1 ~ 2명팀원과 함께 진행할 예정이다.

### 1. 기존 싱기버스 출력물 및 참고 링크 
> * https://www.thingiverse.com/thing:1639224
> 

### 2. 기존 설계 개선품 (Footer) 영역 출력물 참고 링크 
> * https://www.thingiverse.com/thing:5418582

### 2. 개발 기간 
>* 소프트웨어 개발 : 진행중.
>
### :dizzy: 개발 진행중 2022 / 06 / 24 ~ 진행중

### 총 수행기간 : 진행중. 
> * 3D 프린터 출력 기간 : 2022 / 06 /24 ~ 진행중.
> * 눈부심을 막아주는 쉐이더 출력기간 : 
> * 라즈베리파이 제로를 이용한 개발 기간 : 
> * 전자 회로작업 (납땜, 회로기판 작업등) :

### 3. 기존 기능 요구사항 (목표)
<!-- ✅ - 백업-->
> * 개발시 필수로 반드시 들어가야하는 조건 
> * 1. 휴식 모드 
> * 2. 학습 모드 - ( 언어 모드 , 수리 모드 , 음악 (창의) 모드)
> * 3. 수리 모드 
> * 4. 초록 (단색모드)
> * 5. 파랑 모드 (단색모드)
> * 6. 취침 모드 (눈에 피로하지 않은 주광색으로 표시되어지다가 일정 시간이 지나면 자동을 종료되는 기능 구현) - 60분후 자동으로 종료 기능 구현 
> * -> 4분후 자동으로 lcd 화면 꺼짐 , 56분 ( 종료 4분전에 ) 자동으로 화면이 켜짐 기능 추가 
> * 7. 클럽 및 디제잉 파티모드 ( EDM의 노래의 3개의 샘플을 들은후 그노래의 패턴에 맞춰 작동하는모드 )- (아날로그 사운드 센서 사용 구현)
> * 8. 가변저항으로 밝기 조정 가능해야함 
> * 9. 리셋을 버튼을 가능하게 해야함
> * 10. 버튼으로 옵션을 선택할수있어야함
> * 11. 색상 모드 변경이 가능해야함 
> * 12. LED반반 제어모드르 설정해야함 
> * 13. 기기를 사용하지 않을때 1분 경과후 자동으로 lcd 백라이트가 꺼짐 

### 3+@. 신규 업데이트 기능 요구사항 (목표)
> * 14. 다시 사용했을때 확인 버튼을 클릭하면 다시 lcd 백라이트가 켜짐 
> * 15. PIR 센서를 이용 착석했을때 자동으로 전등이 켜짐 ( 조도센서 활용)
> * 16. 라즈베리 파이 제로를 이용하여 웹에서 Led Bridge를 제어할수있다.
> * 17. 기존 Ver1에 있는 기능을 그대로 이어 업데이트한다. 
> * 18. 출력물 품질을 개선하여 최대한 통일된 색상으로 구현한다.

### 3-1. 기능 요구사항 테스트 결과 
### 기능 구현율 진행중 
<!--![스크린샷 2022-02-25 17 44 25](https://user-images.githubusercontent.com/92977647/155683797-0e31044b-ae6e-47e6-8ad0-aa758f999d8d.png)-->

### 4. 개발 언어 및 환경 

### 4-1. 회로도 (기존 버전)
<img src = "https://user-images.githubusercontent.com/92977647/156000794-a0b0d721-42a9-40f5-8a3a-fba1baf2c9ef.png" width="480" height="264"/>

### 5. 3D 프린터 출력 이미지 (제작 과정 진행중..) 
<table>
  <tr>
<td> <img alt="" src = "https://user-images.githubusercontent.com/92977647/151405882-868e048f-3da1-43c8-b910-628e1545a484.gif" width="480" height="264/"/></td>

   </table>

### 6. 완성후 예상 결과물 
<img src = "https://user-images.githubusercontent.com/92977647/151407579-443d4673-a5aa-4c58-9bc1-738e3418344e.png" width="480" height="264"/>
출처 : https://www.thingiverse.com/thing:1639224

### 6-1. 완성후 결과물 

### 7. 저작권 라이센스 (License)
> * Led Bridge parts Stl 설계 파일은 원저작자 : <b>Janis Jakaitis </b>님에게 있습니다.
> * 아두이노 프로그래밍 및 회로 기판 관련 라이선스 :
> * Copyright @2022 ING's TEC (Nifskor) and Creative Commons ![스크린샷 2022-02-23 21 10 25](https://user-images.githubusercontent.com/92977647/155316914-dff67ba7-9236-44d7-8d93-66aae4ec8d77.png)
> * 개인적 용도로 출처를 남긴 후 동일 조건 변경은 허용되지만  상업적 용도는 허용하지 않습니다 - 문의 : (nifskr@naver.com)

