# installation
### CentOS 7
The `exit` command is there because you need to restart your bash session for the new docker group to be applied
```bash
curl https://get.docker.com | sudo bash
sudo usermod -aG docker $(whoami)
sudo systemctl restart docker
sudo systemctl enable docker
```

