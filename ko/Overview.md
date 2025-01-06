# Veritas Backup 개요
**Storage > Veritas Backup > 개요**
Veritas Backup은 파일과 데이터베이스(DB)를 모두 백업할 수 있는 종합 백업 솔루션입니다. 온프레미스와 클라우드 환경에서 모두 사용 가능하며, 데이터 손실 위험을 최소화하고 시스템 장애 시 신속한 복구를 지원합니다.<br> 자동화된 백업 스케줄링과 중복 제거 기능을 통해 스토리지 비용을 절감하고, 복잡한 IT 환경에서도 다양한 데이터베이스와 애플리케이션을 안정적으로 관리할 수 있습니다. Veritas Backup은 기업의 데이터 보호 및 비즈니스 연속성을 보장하는 솔루션입니다.

![NHN Cloud_Guide overview_VeritasBackup_800](https://github.com/user-attachments/assets/39d50e05-c4ae-4b14-a001-b60b5b6b5fe9)

## Veritas Backup 주요 기능

* 종합 백업 솔루션
  * 파일뿐만 아니라 중요한 데이터베이스(DB)까지 안전하게 백업하여 기업의 모든 데이터를 종합적으로 보호합니다.
* 최적화된 관리
  * 시스템 장애나 데이터 손실 시 신속한 복구를 제공하여 비즈니스 다운타임을 최소화하고 업무 연속성을 보장합니다.
  * 중복 제거 및 데이터 압축 기술을 통해 스토리지 사용을 최적화하고, 대용량 데이터도 경제적으로 관리할 수 있습니다.
* 다양한 환경 지원
  * 온프레미스, 클라우드, 하이브리드 등 다양한 환경에서 원활하게 작동하여 다양한 IT 인프라를 갖춘 기업에게 최적화된 백업 솔루션을 제공합니다.
  * 다양한 유형의 데이터베이스와 애플리케이션을 지원하여 복잡한 환경에서도 안정적이고 유연한 백업 및 복구를 제공합니다.
* 편리한 백업 설정 지원
  * 백업 주기
    * 백업 주기를 매주, 매월 선택할 수 있으며, 주 선택 시 특정 요일, 월 선택 시 특정 일자를 복수 선택할 수 있습니다.
  * 백업 시각
    * 1분 단위로 백업 시작 시각을 선택할 수 있습니다. 신청 당일보다 이전 시간을 선택하면 설정한 다음 날짜에 맞추어 백업이 시작됩니다.
  * 백업 보관 주기
    * 2주 또는 4주로 보관 주기를 선택할 수 있으며, 4주 이상의 데이터 보관이 필요한 경우 별도 문의가 필요합니다.
  * 백업 결과 조회
    * **백업 신청 내역 > 리포트** 탭에서 상세 내역을 확인할 수 있습니다.

## 지원하는 운영체제

Veritas Backup에서 지원하는 운영체제는 다음과 같습니다.

| 운영체제 | 하드웨어 아키텍처 | 지원 버전 |
| --------------- | --------------- | --------------- |
| Ubuntu | x64 | Ubuntu Server 20.04.6 LTS<br>Ubuntu Server 22.04.4 LTS<br> |
| Debian| x64 | Debian 11.10 Bullseye<br>Debian 12.6 Bookworm<br> |
| Window Server| x64 | Window Server 2016 STD EN<br>Window Server 2016 STD KR<br>Window Server 2019 STD EN<br>Window Server 2019 STD KR<br>Window Server 2022 STD EN<br>Window Server 2022 STD KR<br> |
| CentOS| x64 | CentOS 7.9 |
| Rocky| x64 | Rocky Linux 8.10 |


## 참고 사항

### 백업 소프트웨어
* Veritas Netbackup
### 백업 프로그램 설치 위치
* Linux: /usr/openv/netbackup
* Windows: C:\Program Files\Veritas
### 백업 프로그램 데몬(프로세스) 정보
* Linux: /usr/openv/netbackup/bin/bpps -x
* Windows: C:\Program Files\Veritas\Netbackup\bin\bpps.exe<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RUN - Services.msc - NetBackup Process
