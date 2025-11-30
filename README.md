# simple-java-monolith-app
This is a simple java monolith application based on below folder structure.
simple-monolith/
├─ pom.xml
├─ Dockerfile
├─ .dockerignore
├─ src/
│  ├─ main/
│  │  ├─ java/com/mithuntech/
│  │  │  ├─ SimpleMonolithApplication.java
│  │  │  ├─ controller/
│  │  │  │  └─ HelloController.java
│  │  │  └─ service/
│  │  │     └─ GreetingService.java
│  │  └─ resources/
│  │     └─ application.properties
│  └─ test/
│     └─ java/com/mithuntech/
│        └─ controller/
│           └─ HelloControllerTest.java
└─ .github/workflows/
   └─ ci-cd.yml   (GitHub Actions example)
└─ Jenkinsfile    (Jenkins pipeline example)
