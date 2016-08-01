ansible-playbook -i ansible.inventory provision.ansible.yaml --limit=staging


TODO
1)  패브릭 배포 처리를 Ansible로 변경
2) 로컬 VM을 가동하기 위한 Vagrant 이용 (혹은 Docker)
  스테이징 사이트에서 테스트를 실행하는 것은 실제 운영 서버에서도 문제 없이 동작할 수 있다는 자신감을 준다.
  하지만 굳이 스테이징 서버가 아니라도 가상머신(VM)을 로컬 장비에 설치해도 동일한 효과를 볼 수 있다.

  Vagrant 개발 서버(혹은 Docker)를 로컬 PC에 설치하고, 코드를 개발 서버에 배포하도록 한다.
  로컬 VM에서 FT 수행 후, 이상 없을 경우
  운영 서버에 배포한다햣