
# Login Steps


Update packages and install Go 

    # apt update 
    # apt install golang-go -y

Get the code from git

    # git clone https://github.com/sreenathzs/login.git
    # cd login

Move systemd file 

    # mv systemd.service /etc/systemd/system/login.service

Build the code 

    # go build 

If any dependency needed download using  
    # go get <dependency>
    # go build

Start the services 

    # systemctl daemon-reload 
    # systemctl start login
    # systemctl enable login
    # systemctl status login

Or

    # ./login
[Screenshot (340)](https://user-images.githubusercontent.com/82632135/116676138-3f8fb980-a9c4-11eb-90f3-d978aa34a4e3.png)
