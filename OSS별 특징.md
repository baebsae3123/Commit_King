대표적 OSS 라이선스

1. 카피레프트(Copyleft) 계열
-GPL (GNU General Public License)
가장 널리 알려진 카피레프트 라이선스로 GPL 코드를 사용하여 개발된 프로그램은 전체 소스 코드를 반드시 GPL로 공개해야 함.
예시: Linux 커널, Git, MariaDB

-AGPL (GNU Affero General Public License)
GPL과 유사하나, 네트워크를 통해 소프트웨어를 사용하는 경우에도 소스 코드 공개 의무를 지켜야함.

-LGPL (GNU Lesser General Public License)
GPL보다 완화된 조건으로, 라이브러리로 사용하는 경우 라이브러리 자체의 수정본만 공개하면 되고 이를 사용하는 주 프로그램은 비공개로 유지할 수 있음.

-EPL (Eclipse Public License)
약한 카피레프트 성격으로, 주로 모듈 단위로 소스 공개 의무가 발생하여 상업적 통합이 비교적 쉬움. 수정한 모듈 및 파생 코드는 EPL로 공개해야 함.
예시: Eclipse IDE

2. 퍼미시브(Permissive) 계열
-MIT License
가장 느슨한 조건의 라이선스로, 라이선스와 저작권 고지사항을 유지하기만 하면 소스 코드 공개 의무 없이 상용 소프트웨어에 포함하여 배포할 수 있음.
예시: Bootstrap, Angular.js, jQuery

-Apache License 2.0
MIT와 유사하게 매우 자유롭지만 특허 관련 조항이 포함되어 있음. 수정 후 배포 시 Apache 라이선스를 명시해야함.
예시: Android, Hadoop, Apache Tomcat

-BSD License (Berkeley Software Distribution)
MIT와 함께 대표적인 퍼미시브 라이선스로, 라이선스 고지사항만 유지하면 자유롭게 사용 가능.

다양한 OSS

1. 버전 관리 OSS

-Git
소프트웨어의 소스 코드 관리를 위해 개발된 가장 대표적인 분산 버전 관리 시스템(DVCS)
라이선스: GPL

-Subversion (SVN)
Git이 등장하기 전까지 가장 널리 사용되던 중앙집중식 버전 관리 시스템(Centralized VCS).
라이선스: Apache License.

-Mercurial
Git과 유사한 분산 버전 관리 시스템(DVCS).
라이선스: GPL/LGPL.

2. 운영체제 및 시스템 OSS

-Linux
서버, 임베디드 장치(IoT), 슈퍼컴퓨터, 그리고 Android 운영체제의 기반이 되는 커널(Kernel).
라이선스: GPLv2.

-Android
모바일 기기의 운영체제. Google이 개발하지만, 핵심 부분은 AOSP(Android Open Source Project)로 공개되어 있음.
라이선스: Apache License 2.0 및 기타

3. 데이터베이스 및 미들웨어 OSS

-MySQL & MariaDB
세계적으로 가장 널리 사용되는 관계형 데이터베이스 관리 시스템(RDBMS). MariaDB는 MySQL에서 파생됨.
라이선스: GPL

-PostgreSQL
엔터프라이즈급 기능을 갖춘 강력한 객체-관계형 데이터베이스.
라이선스: PostgreSQL License(퍼미시브 계열)

-Apache HTTP Server
전 세계적으로 가장 널리 사용되는 웹 서버 소프트웨어 중 하나임.
라이선스: Apache License 2.0

-Nginx
고성능 웹 서버 및 리버스 프록시, 로드 밸런서로 인기가 높음.
라이선스: 2-Clause BSD License(퍼미시브 계열)

4. 클라우드 및 컨테이너 OSS

-Docker
애플리케이션을 컨테이너라는 독립적인 환경으로 패키징하고 배포하는 데 사용됨.
라이선스: Apache License 2.0

-Kubernetes (K8s)
Docker와 같은 컨테이너를 대규모로 자동 배포, 확장, 관리하는 오케스트레이션 시스템의 사실상 표준이됨.
라이선스: Apache License 2.0
