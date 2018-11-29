# installation
### CentOS 7
The `exit` command is there because you need to restart your bash session for the new docker group to be applied
```bash
sudo yum update -y
sudo yum install -y docker
sudo groupadd docker
sudo usermod -aG docker $(whoami)
sudo systemctl enable docker
sudo systemctl start docker
exit
```

