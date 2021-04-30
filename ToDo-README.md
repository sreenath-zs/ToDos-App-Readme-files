# ToDo Steps 


Update the Packages

    # apt update
    # apt install npm

Clone the Git repo 

    # git clone https://github.com/sreenathzs/todo.git

Naviagte to todo

    # cd todo

Move systemd  file 

    # mv systemd.service /etc/systemd/system/todo.service



Now build the code 
 
    # npm install 
    # npm run build 

Configuration // Redis_Host & PORT 

Start the services
    # /etc/systemd/system/todo.service(Set Environment )

    # systemctl daemon-reload
    # systemctl start todo 
    # systemctl enable todo 
    # systemctl status todo 

 
  or

start the service
 
    # npm start 
Here sometimes App crash, then we kill the nodes by using below commands
    
    # killall node
    # npm start

![Screenshot (341)](https://user-images.githubusercontent.com/82632135/116676372-88e00900-a9c4-11eb-8c03-a31d7571ddcb.png)
![Screenshot (342)](https://user-images.githubusercontent.com/82632135/116676381-8a113600-a9c4-11eb-9388-7534a24df827.png)


