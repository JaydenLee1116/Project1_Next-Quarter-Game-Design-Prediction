# Project1_Next-Quarter-Game-Design-Prediction

## What games should I design next quarter?

상황 : 게임회사 데이터팀 합류

문제 : '다음 분기에 어떤 게임을 설계해야할까'

### Data Description

Name : 게임의 이름입니다.<br>
Platform : 게임이 지원되는 플랫폼의 이름입니다.<br>
Year : 게임이 출시된 연도입니다.<br>
Genre : 게임의 장르입니다.<br>
Publisher : 게임을 제작한 회사입니다.<br>
NA_Sales : 북미지역에서의 출고량입니다.<br>
EU_Sales : 유럽지역에서의 출고량입니다.<br>
JP_Sales : 일본지역에서의 출고량입니다.<br>
Other_Sales : 기타지역에서의 출고량입니다.<br>

### Set Assuming

출고량 : 제작사가 상품을 생산한 개수(중간 도소매업자에게 넘어간 양)<br>
판매량 : 실제 상품을 (최종)소비자에게 판매가 된 개수<br>

가정1 : "출고된 게임은 전부 소비자에게 판매가 되었다.('출고량' == '판매량')"<br>
가정2 : "각 지역 별 출고된 상품들은 그 지역의 소비자에게 판매가 되었다."<br>
가정3 : "판매량과 소비자의 게임 선호도는 양의 관계를 따른다."<br>
