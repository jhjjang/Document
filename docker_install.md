```
#!/bin/bash
sudo docker apt-get update
sudo apt-get install docker.io
sudo usermod -aG docker $USER
sudo docker pull jhjang/develop:0.2
sudo docker run -it --name shoplinker -v /data/shoplinker:/data/shoplinker -p 80:80 jhjang/develop:0.2
```
