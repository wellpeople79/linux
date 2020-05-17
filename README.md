# linux

1.리눅스 명령어

* 실행중인 서비스 조회

service --status-all|grep +

[ + ]는 실행 중(running)임을, [ – ]는 실행 중이 아님을 나타냄

‘|grep +’를 붙이면 실행 중인 서비스 만을 출력함.

* 배포판 버전확인

grep . /etc/issue*

* 버전확인2

rpm -qa *-release

* 버전확인3

grep . /etc/*-release

* root password 변경

sudo passwd root
