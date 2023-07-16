# PMS-Project
>  ## :page_with_curl:개요 및 기획의도
 - JSP/Servlet을 활용한 팀 프로젝트입니다.
 - **PMS** 란 Project Manage service의 약자로 프로젝트에 대한 전반적인 일정관리 프로그램입니다.

### Why:question:
- 팀 프로젝트 진행시 본인의 업무가 전체 프로젝트 일정에서 얼마나 진행되었고 언제까지 진행되어야 하는지 한눈에 파악하기 어려웠습니다.
- 팀원이 맡은 업무가 헷갈리는 경우가 있었고 재차 확인해야 하는 번거로움이 있었습니다.  
### So:exclamation:
- 개발자로 사용자층을 정하고 개발관련 프로젝트 진행절차를 관리해주는 일정관리 프로그램 만들기를 기획했습니다.
- 진행중인 프로젝트, 종료된 프로젝트 등 전체 프로젝트에 대한 일정과 산출물 등을 간편한 UI를 통해 보다 쉽게 확인할 수 있도록 기획했습니다.



</br>
</br>

> ## 개발기간 및 :wrench:사용 기술  
### :calendar:기간:2023.05.26 ~ 2023.06.09 

### ✔️Frond-end
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"> <img src="https://img.shields.io/badge/Css-1572B6?style=for-the-badge&logo=Css3&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
### ✔️Back-end
<img src="https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
</br>
</br>
</br>



> ## :couple: 팀원 역할분배
<p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/8e92246e-b0f4-475e-9e7b-9bfc001403f9" width="550" height="400"/></p> 

</br></br>


> ## :keyboard:DB 설계
<p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/304795d2-d019-43c9-944a-134d77cb1632" width="550" height="400"/></p>   

</br></br>

> ## :bulb:주요 서비스

|**메인화면** |  
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/0f77bd19-4b99-4616-986d-4e56bc9722d4" width="550" height="400"/> </p>|
|**:clipboard:구현내용** </br></br>로그인시 보이는 메인화면입니다. 메인화면에서는 상단부는 본인 프로젝트 진행중 결재안건, 작업, 이슈 등을 숫자로 표현하여 그때그때 확인할 수 있게 구현했습니다.</br>중단부에서는 전체 프로젝트 진행현황과 본인의 작업이 어느정도 진행되었는지 amcharts4 차트 라이브러리를 사용하여 표현했습니다. |

|**프로젝트 상세정보 및 비용 등록**|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/dcd30690-018d-4d5f-8243-8f05c4c32c94" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 프로젝트 센터 클릭시 전체 프로젝트 리스트를 출력해줍니다. 프로젝트를 선택하면 해당 프로젝트에 대한 상세정보를 보여주는 페이지를 보여줍니다.</br>프로젝트 상세정보에서는 프로젝트 진행시 사용했던 비용을 등록 수정 삭제할 수 있습니다.|

|**프로젝트 WBS 차트 출력**| 
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/ba57ddaa-a278-49b4-9d0a-e370d97a9177" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> wbs차트 탭을 클릭하면 해당 프로젝트 업무 진척도를 날짜별로 확인할 수 있는 차트가 출력됩니다.|

|**본인이 진행한 작업 목록과 완료율 출력**|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/fda171e5-afab-45fc-a0ec-84b0ecef4558" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 작업관리 세부탭에서 내작업 선택시 본인이 진행했던 작업리스트를 출력하고 완료율을 변경할 수 있습니다. 100%가 되지 않으면 진행중이란는 문구를 보여주고 100%가 되면 완료로 바뀌도록 구현했습니다.|

|**팀원별 맡은 업무에 대한 진행율 차트 출력**|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/ce925076-caaf-4218-8c57-002a38dd4c62" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 작업관리 > 일반작업 탭을 클릭하면 해당 프로젝트에서 팀원들의 작업 진행 상황을 도넛차트로 보여줍니다. |

|진행했던 프로젝트 산출물 조회 및 다운로드|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/489d09f5-59d5-4fc6-bb37-8bf2ee3f9fa6" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 프로젝트를 진행한 팀원은 본인의 산출물을 등록하고 해당 프로젝트에서 나온 산출물을 다운로드 받을 수 있습니다.|


|팀원 일정 확인 캘린더|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/58b0c4db-a511-492d-bc60-b4da569be0eb" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 개인 및 팀원의 일정을 확인할 수 있는 캘린더입니다. 프로젝트를 진행하는 팀원의 개별 인원의 셀렉트 박스를 클릭하면 해당 인원의 일정을 달력에 보여주며 월별로 조회가 가능합니다.|


|결재안건 관리 기능|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/5e13fb6c-5802-4fec-aaaa-8a20b142e126" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 결재안건을 관리할 수 있는 기능입니다. PA는 업무와 관련된 결재를 요청할 수 있고 PM은 PA가 요청한 결재건에 대해 승인 여부를 선택해 해당 건을 처리할 수 있습니다 결재의 승인여부는 결재 상세정보 페이지에서 확인할 수 있습니다.|

|이슈안건 관리 기능|
|-------------|
| <p align="center"><img src="https://github.com/ukkkk7/PMS-Project/assets/117158625/c2e03d35-eb9a-47a9-96b5-b89fae1a308f" width="550" height="400"/></p>|
|**:clipboard:구현내용** </br></br> 프로젝트 진행시 발생한 이슈를 관리할 수 있는 기능입니다. 결재기능과 마찬가지로 PM은 요청받은 이슈에 대해 조치여부를 결정하고 이슈 상세정보에서 조치여부를 확인할 수 있습니다.|









