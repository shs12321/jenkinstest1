# jenkinstest1
#아티팩토리가 깨져서 11:20분에서 시험 시작하여
#담임선생님 - 강사님 동의하여 추가 제출하였습니다.

#sol1 Build
'''
https://bitbucket.org/jgnam/base/src/master/
로 부터 소스를 내려받아 gradle로 빌드
'''

#Artifactory
'''
플러그인을 이용하여 아티팩토리 서버로 보냄
'''

#sol1 Build
'''
git으로
https://shs12321@bitbucket.org/jgnam/base.git로 부터 소스를 내려받아 sol2 job에서 빌드
'''

#tomcat
'''
trigger를 이용하여 sol2 빌드가 완료되면
war파일을 찾아서 플러그인을 이용하여 7버전 톰캣 서버로 보냄
'''

![sol1 아티팩토리에 잘 전달된 스크린샷](art.PNG)

![sol1 Jenkins에서 빌드가 완료된 스크린샷](build.PNG)

![sol2 Tomcat 7.x버전에 올린 매니저 접속 스크린샷](캡쳐.PNG)

![sol2 Jenkins에서 sol2기반으로한  deploy_tomcat의 빌드가 완료된 스크린샷](pipe.PNG)


![가점2 sol1 git fork떠서 실행](base.PNG)
![가점2 sol2 git fork떠서 실행](webapp.PNG)


![가점1 소스코드 화면 수정 전 스크린샷](tomcat.PNG)
![가점1 소스코드 화면 수정 후 스크린샷](tomcat0.PNG)
