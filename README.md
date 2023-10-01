# Django-todo
A simple todo app built with Django is used in this CI/CD project

Pre-requisites for this project are
1. Pre-built app
2. AWS EC2 instance with docker and Jenkins installed
   
The steps to do app deployment through CI/CD are
1. DockerFile should be created with the specific commands.  #present in my repo uploaded
  ![image](https://github.com/hijackhim/todo-cicd-app/assets/105789918/589f6b75-312a-4a9a-9287-a13651fbe896)
2. GitHub should be integrated with Jenkins by using the "git server" plugin.
3. Github token is recommended for authentication purposes in Jenkins
4. for Jenkins to use your GitHub account setting should be like this
 ![image](https://github.com/hijackhim/todo-cicd-app/assets/105789918/34714b55-0db4-42b1-a4d1-a9993df4228f)
5. Under build step in the setting on the same page as above commands.
   ![image](https://github.com/hijackhim/todo-cicd-app/assets/105789918/1972b494-3c70-4d66-b57a-0dccf1f1b3f9)
6. The above command will use DockerFile(created in the initial steps) to automate our tasks.
7. While building the Jenkins pipeline, console output will look like this
   ![image](https://github.com/hijackhim/todo-cicd-app/assets/105789918/c768d997-2008-4a99-9e9a-75db3d81b83d)
8. after successful build, you will be able to access the app in your browser with your VM or Cloud public IP and port for example-http://54.173.216.194:8000/
   ![image](https://github.com/hijackhim/todo-cicd-app/assets/105789918/e26fa739-7415-4676-b888-60a98ac04436)


That's it thanks for reading


  

