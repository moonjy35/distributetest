신규 사이트 프로비저닝
======================

## 필요 패키지

* nginx
* Python 3
* Git
* pip
* virtualenv

Ubuntu 14.04

sudo apt-get install nginx git python3 python3-pip
sudo pip3 install virtualenv

## Nginx 가상 호스팅 설정
* nginx.template.conf 참고
* SITENAME 부분을 적절하게 수정함

## Upstart Job
* gunicorn-upstart.template.conf 참고
* SITENAME 부분을 적절하게 수정함


