## Setup Kali Linux

```shell
sudo apt update
sudo apt full-upgrade -y
```
```shell
cd Downloads
sudo apt install ./google-chrome-stable_current_amd64.deb
```
```shell
cd Downloads
tar -xf pycharm-professional-2021.1.tar.gz
sudo mkdir /opt/jetbrains
sudo mv pycharm-2021.1 /opt/jetbrains
/opt/jetbrains/pycharm-2021.1/bin/pycharm.sh
```
```shell
sudo apt install python3-pip
pip install pipenv
```
```shell
sudo apt remove cmdtest
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update
sudo apt install yarn
yarn  --version
```