# 2021_information_protection

# 정보보호와 보안 AI 악성코드 탐지 프로젝트 11조


[팀원]  
김진수(20141897)[정보보안암호수학과] (자퇴)  
전현근(20153224)[소프트웨어학부]  
장성용(20162838)[소프트웨어학부]  

## 프로젝트 내용
pe 파일이 주어졌을 때, 주어진 파일이 악성파일인지 정상파일인지 판별하는 '이진분류기 모델'을 만든다.

pe파일
Portable Excutable 파일
윈도우 상에서 실행 가능한 프로그램
ex) exe dll sys 등등

## 진행사항
class EmberParser:
 import 하는 라이브러리
    def imports_info(self):
 악성코드의 경우 export 할 것
    def exports_info(self):
  데이터 디렉토리   
 def get_datadirectories_info(self):
 
class PestudioParser:
이미지
def get_image_info(self):
인증서가 있으면0, 없으면1
def get_certificate_info(self):
