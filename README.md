# DevopsAL
# 5mayTask
In this task we have to create 3 different jobs(on Jenkins) for testing and uploading to server for client usage. In this 1st job is to launch an OS {using docker image of HTTPD} whenever Jenkins detect any change in branch (dev1) for testing.In 2nd job Jenkins launch another OS {using dokcer image of HTTPD} whenever it detects changes at master for client usage. In 3rd job QAT will test the output and quality of software by performing different number of tests.
In this we use knowledge of docker,jenkins,Git,Github,Redhat-8,and many more small software {like ngrok}.
In this project we initially create a html file named web.html. Then we create branch{master & dev1}. Then we put it on Github using Git. Then we integrate Jenkins with Github {perform actions like built trigger,plugins,webhooks,. create jobs as per the requirment}. Then do further steps on Redhat-8 for pulling HTTPD image,for runing docker.
