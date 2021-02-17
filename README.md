# T05 - SOEN 487
This is the template provided to make Server Side and Client Side for Tutorial 5. You should watch the tutorial first and then follow the read me file.
# Making ServerSoap
For making the Server for the project, the project can be made in the way that is described in the Project Setup Section. Then, you have to make the bellow items:
1) The Service Interface 
2) The Service Implementation 
3) The Person POJO Class 
4) The SOAP Fault 
5) The Publisher.
# Making ClientSoap
For making the Client Side for the project, the project can be made as follow:
File --> New -->Project --> Maven --> Choosing the name of the project and Group ID
# Importing the services from ServerSoap
1) Open Command Prompt.
2) Go to the root that the ClientSoap is made.
3) Run the bellow command:
 wsimport -d src/main/java -p com.soen487.t05.client –keep http://localhost:8088/WebServiceDemo/Welcome?wsdl
 # Soap UI Testing
To test with SoapUI, run the program and click on new SOAP project. While ServicePublisher is still running, enter a project name and copy the WSDL url in the initial WSDL field.
![image](https://user-images.githubusercontent.com/63208813/108148756-7a5da300-709f-11eb-8663-2315a574a368.png)


