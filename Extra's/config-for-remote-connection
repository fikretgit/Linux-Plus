# Read more about SSH config files: https://linux.die.net/man/5/ssh_config
Host control-node     # host name, can be anything you want
    HostName 54.173.110.192   # <public ip of resources>
    IdentityFile ~/.ssh/felix.pem  # path of pem file
    User ec2-user     # name of user
Host ubuntu
    HostName 44.208.35.227
    IdentityFile ~/.ssh/felix.pem
    User ubuntu
Host *
    TCPKeepAlive yes
    ServerAliveInterval 120
