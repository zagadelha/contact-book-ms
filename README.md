# Contact-Book-Ms
A sample project built in microservices based with Spring

## Goals
- Creation of a distributed project in microservices using Spring Boot
- Creation of gateway for all requests and just it know de services hosts
- Creation of a remote central point of configuration using Github

## Technologies
- Java 11 (Should work in another versions, but is not tested)
- Spring Boot 2.5
- Eureka Server 3.0
- Spring Gateway 3.0
- H2 Memory Database 1.4

## Architecture
![image](https://user-images.githubusercontent.com/2160083/122096175-a508ff80-cde4-11eb-8669-9710644513f5.png)

## Resources / Endpoints
- List Contacts: http://localhost:8989/contact-book/list
- Get Contact: http://localhost:8989/contact-book/1
- Add Contact: http://localhost:8989/contact-book/add
- Edit Contact: http://localhost:8989/contact-book/edit
- Delete Contact: http://localhost:8989/contact-book/remove/1



