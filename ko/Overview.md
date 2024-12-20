# Veritas Backup 개요

Veritas Backup은 파일과 데이터베이스(DB)를 모두 백업할 수 있는 종합적인 백업 솔루션입니다. 온프레미스와 클라우드 환경에서 모두 사용 가능하며, 데이터 손실 위험을 최소화하고 시스템 장애 시 신속한 복구를 지원합니다.<br> 자동화된 백업 스케줄링과 중복 제거 기능을 통해 스토리지 비용을 절감하고, 복잡한 IT 환경에서도 다양한 데이터베이스와 애플리케이션을 안정적으로 관리할 수 있습니다. Veritas Backup은 기업의 데이터 보호 및 비즈니스 연속성을 보장하는 솔루션입니다.



## 서비스 특징

* 파일뿐만 아니라 중요한 데이터베이스(DB)까지 안전하게 백업하여, 기업의 모든 데이터를 종합적으로 보호합니다.
* 시스템 장애나 데이터 손실 시,  신속한 복구를 제공하여 비즈니스 다운타임을 최소화하고 업무 연속성을 보장합니다.
* 온프레미스, 클라우드, 하이브리드 환경에서도 원활하게 작동하여 다양한 IT 인프라를 갖춘 기업에게 최적화된 백업 솔루션을 제공합니다.
* 중복 제거 및 데이터 압축 기술을 통해 스토리지 사용을 최적화하고, 대용량 데이터도 경제적으로 관리할 수 있습니다.
* 여러 유형의 데이터베이스(DB)와 다양한 애플리케이션을 지원하여, 복잡한 환경에서도 안정적이고 유연한 백업 및 복구를 제공합니다.

### 백업 주기
* 매 주, 매 월 선택이 가능하며 주 선택 시 특정 요일, 월 선택 시 특정 일자를 복수 선택할 수 있습니다.

### 백업 시각
* 1분단위로 백업 시작 시각을 선택 할 수 있습니다. 신청 당일보다 이전 시간을 선택 시 설정한 다음 날짜에 맞추어 백업이 시작됩니다.
* 백업 작업은 비즈니스에 영향을 최소화하기 위해 비업무 시간에 설정하는 것을 추천드립니다.

### 백업 보관주기
* 2주, 4주의  보관주기를 선택 할 수 있으며 4주 이상의 데이터 보관이 필요한 경우 별도 문의가 필요합니다.

### 백업 결과조회
* 백업 신청 내역 > 리포트 탭 메뉴에서 상세 내역의 확인이 가능합니다. 

## 지원하는 운영체제

Veritas Backup에서 지원하는 운영체제는 다음과 같습니다.

| 운영체제 | 하드웨어 아키텍처 | 지원 버전 |
| --------------- | --------------- | --------------- |
| Ubuntu | x64 | Ubuntu Server 20.04.6 LTS<br>Ubuntu Server 22.04.4 LTS<br> |
| Debian| x64 | Debian 11.10 Bullseye<br>Debian 12.6 Bookworm<br> |
| Window Server| x64 | Window Server 2016 STD EN<br>Window Server 2016 STD KR<br>Window Server 2019 STD EN<br>Window Server 2019 STD KR<br>Window Server 2022 STD EN<br>Window Server 2022 STD KR<br> |
| CentOS| x64 | CentOS 7.9 |
| Rocky| x64 | Rocky Linux 8.10 |


## 복구 신청 절차

Veritas Backup에서 백업을 진행하신 이력이 존재하고 복구할 데이터가 유효한 경우만 복구가 가능합니다. 신속하고 원활한 복구 작업을 위하여 담당자가 별도로 연락이 진행될 예정이며, 복구 신청 절차를 참고해주세요.
1. 복구 신청 페이지 진입
2. 복구를 신청할  소스 프로젝트 > 소스 서버 >  복구 시점 및 경로 선택
3. 복구를 받을 타깃 프로젝트 > 타깃 서버 > 복구 경로 선택

복구 신청 후 업무 시간 기준 용량에 따라 상이할 수 있으며 업무 시간(오전 10시 ~ 오후 6시) 이후 신청 건은 익일 업무일에 복구 진행이 됩니다.

## 요금

### 백업

(VAT별도)
<!-- VAT별도는 우측 정렬이 필요합니다. 기획서(https://www.figma.com/design/nRpr7Bz9sLXndbtHEfAIkO/Veritas-Backup-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%86%8C%EA%B0%9C?node-id=0-1&node-type=canvas&t=y0hB3ulN21IOVsCk-0)참고 부탁드립니다. -->
| 과금 구분 | 과금 구간 | 과금 기준 | 요금 |
| --------------- | --------------- | --------------- | --------------- |
| 백업 용량 | 1TB 이하 | 월 정액 과금 | 250,000원 |
|          | 1TB 초과 | 10GB당 백업 용량 누적 | 2,500원 |
<!-- 표에서 백업용량은 아래 행과 머지되어야 합니다. 기획서(https://www.figma.com/design/nRpr7Bz9sLXndbtHEfAIkO/Veritas-Backup-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%86%8C%EA%B0%9C?node-id=0-1&node-type=canvas&t=y0hB3ulN21IOVsCk-0)참고 부탁드립니다.  -->
안내
<!-- 디자인 가이드에서 제공중인 안내 아이콘 이미지를 사용하고 싶습니다. 불가능하다면 이미지 인입하지 않겠습니다. 자세한 내용은 기획서(https://www.figma.com/design/nRpr7Bz9sLXndbtHEfAIkO/Veritas-Backup-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%86%8C%EA%B0%9C?node-id=0-1&node-type=canvas&t=y0hB3ulN21IOVsCk-0) 참고 부탁드립니다.  -->
* 1TB는 1,024GB 기준으로 이용 요금이 청구됩니다.
* 15일 이후 신청 건은 익월 일괄 청구됩니다.




### 복구

(VAT별도)
<!-- VAT별도는 우측 정렬이 필요합니다.  -->
| 과금 구분 | 과금 기준 | 과금 구간 |  | 요금 |
| --------------- | --------------- | --------------- | --------------- | --------------- |
| 일반 복구 | 신청건수 | 1건 |- | 무료 |
|          |  | 1건 초과 시 | 1건당 | 300,000원 |
<!-- 표에서 일반복구와 신청건수는 아래 행과 머지, 과금 구간은 옆의 칸과 머지되어야 합니다. 자세한 내용은 피그마 기획서(https://www.figma.com/design/nRpr7Bz9sLXndbtHEfAIkO/Veritas-Backup-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%86%8C%EA%B0%9C?node-id=0-1&node-type=canvas&t=y0hB3ulN21IOVsCk-0)를 참고해주세요  -->
안내
<!-- 디자인 가이드에서 제공중인 안내 아이콘 이미지를 사용하고 싶습니다. 불가능하다면 이미지 인입하지 않겠습니다. 자세한 내용은은 기획서(https://www.figma.com/design/nRpr7Bz9sLXndbtHEfAIkO/Veritas-Backup-%EC%84%9C%EB%B9%84%EC%8A%A4-%EC%86%8C%EA%B0%9C?node-id=0-1&node-type=canvas&t=y0hB3ulN21IOVsCk-0) 참고 부탁드립니다.  -->
* 복구 서비스는 한 달에 1건 무료로 제공됩니다.
* Veritas Backup 서비스를 이용하고 데이터가 유효한 경우에만 복구가 가능하며, 업무 시간 내에서 일반 복구 서비스가 제공됩니다.  



## 참고 사항

### 백업 소프트웨어
* Veritas Netbackup
### 백업 프로그램 설치 위치
* Linux : /usr/openv/netbackup
* Windows : C:\Program Files\Veritas
### 백업 프로그램 데몬(프로세스) 정보
* Linux : /usr/openv/netbackup/bin/bpps -x
* Windows : C:\Program Files\Veritas\Netbackup\bin\bpps.exe<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RUN - Services.msc - NetBackup Process
