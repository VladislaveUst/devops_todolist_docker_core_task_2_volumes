1. Run MySQL Container with a Volume:
docker run -d -p 3306:3306 --name vladisloveust/mysql-local:1.0.0 -v my-mysql-data:/var/lib/mysql mysql-local:1.0.0 

2. Run Application Container and Connect to MySQL:
docker run -d --name todo_app -p 8080:8080 todoapp:1.0.0 

3. Access the Application in Browser
http://localhost:8080

4. Link to my Docker Hub repository
https://hub.docker.com/repositories/vladisloveust