Apache Spark
============
OKD 클라우드 플랫폼 구축 시 각 세부를 지원하기 위해 Apache Spark에 대한 Docker 이미지와 OKD Cateogry Templdate를 구축하였다.

## Apache Spark
아파치 스파크(Apache Spark)는 오픈 소스 클러스터 컴퓨팅 프레임워크이다. 원래 캘리포니아 대학교 버클리의 AMPLab에서 개발된 스파크의 코드베이스는 나중에 아파치 소프트웨어 재단에 기부되었으며 그 이후로 계속 유지 보수를 해오고 있다. 스파크는 암시적 데이터 병렬성과 장애 허용과 더불어 완전한 클러스터를 프로그래밍하기 위한 인터페이스를 제공한다

## Docker
kubernetes, mesos, yarn 형태로 구성되어 있으면 Dockerfile로 만들어져 있다.

## Template
OKD에서 실행 가능한 template 파일로서 기본적인 구성을 통해 사용자가 컴스텀하게 변경 가능하도록 구성을 했다
