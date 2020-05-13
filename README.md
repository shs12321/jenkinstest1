# jenkinstest1
#아티팩토리가 깨져서 11:20분에서 시험 시작..

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
