
## Pre-reqisite:
Docker must be installed on system.

##Steps:
1. Clone this repository to your local.

2. Change the directory to the jira-software folder where the Dockerfile is located.

3. To create the custom jira image hit this command on terminal `docker build .`

4. You will get the new docker image and can change its name by executing this command on terminal `docker tag <image-id> <new-name>:<tag>`

##Using preconfigured jira image, follow these steps :
1. Pull the image by using command docker pull `<your repo>/jira-software-v0:8.8.0`.

2. Verify if image is pulled by executing the command `docker images`.

3. Now run the image into container `docker run -d -p 8080:8080 <your-repo>/jira-software-v0:8.8.0`.

4. Ensure that container is up by executing `docker container ls`.

5. Now you can access the url `http://localhost:8080/`.

6. The credentials to access the jira is `admin:admin`.