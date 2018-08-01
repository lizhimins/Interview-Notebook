sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3
sudo apt-get install python-pip
sudo pip install --upgrade pip
sudo apt-get install python3-pip
sudo pip3 install --upgrade pip
update-alternatives --install /usr/bin/python python /usr/bin/python2 100
update-alternatives --install /usr/bin/python python /usr/bin/python3 150
sudo update-alternatives --config python
sudo pip3 install jupyter
jupyter notebook --generate-config
PASSWD=$(python -c 'from notebook.auth import passwd; print(passwd("jupyter"))')
echo "c.NotebookApp.password = u'${PASSWD}'"
sudo vim /root/.jupyter/jupyter_notebook_config.py
sudo vim /etc/init/jupyter.conf
sudo apt-get install nignx
history
apt-get install nignx
sudo apt-get install nginx
jupyter notebook & --allow-root
sudo vim /root/.jupyter/jupyter_notebook_config.py
sudo apt-get install nginx
sudo start jupyter
jupyter notebook
start jupyter
apt instll upstart
apt install upstart
jupyter notebook & --allow-root
sudo dpkg-divert --local --rename --add /sbin/initctl
ln -s /bin/true /sbin/initctl
start jupyter
jupyter notebook & --allow-root
jupyter notebook --allow-root
jupyter notebook &--allow-root
jupyter notebook --allow-root
jupyter notebook& --allow-root
jupyter notebook --allow-root
top
ls
cd /
ls
jupyter notebook &--allow-root
jupyter notebook --allow-root
jupyter notebook& --allow-root
sudo start jupyter
sudo restart jupyter
nohup jupyter notebook & --allow-root
nohup jupyter notebook --allow-root &
wget http://everybest.oss-cn-shanghai.aliyuncs.com/vim_test_linux
ls
./vim_test_linux
chmod 777 vim_test_linux
./vim_test_linux
./vim_test_linux
ls
rm -rf vim_test_linux
ls
clear
history