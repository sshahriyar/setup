setup.git
=========
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
ssh-keygen -t rsa -C "youremail@mail.com"
# press enter two to three times
# Add key on github
git clone https://github.com/sshahriyar/setup.git
./setup/setup.sh   
```


[Reference: Video Lectures 4a/4b] https://class.coursera.org/startup-001/lecture/index





