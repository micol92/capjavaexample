# capjavaexample

https://developers.sap.com/tutorials/cloudsdk-integrate-cap.html 에 대해 에러가 발생하면 아래와 같이 수정하시면 됩니다.

Step1) 
mvn archetype:generate -DarchetypeArtifactId=cds-services-archetype -DarchetypeGroupId=com.sap.cds -DarchetypeVersion=RELEASE \
-DgroupId=com.sap.cap -DartifactId=capbizservice

Step5)
 import 부분은 소스 파일 참조.

Step7)
export destinations='[{name: "MyABAPSystem", url: "http://localhost:3000"}]'
