##### links 

[GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker](https://www.youtube.com/watch?v=R8_veQiYBjI) (this example is based on this tutorial)  
[Original code](https://github.com/nanuchi/my-project)  
[Docker Build & Push Action](https://github.com/mr-smithers-excellent/docker-build-push)  

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
