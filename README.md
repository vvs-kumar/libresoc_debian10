sudo apt install python3-pip
sudo apt-get install vim exuberant-ctags
sudo apt-get install build-essential
sudo apt-get install git python3.7 python3.7-dev python3-nose
sudo apt-get install graphviz xdot gtkwave
sudo apt-get install python3-venv
sudo apt-get install python-virtualenv # this is an alternative to python3-venv
sudo apt-get install tcl-dev libreadline-dev bison flex libffi-dev iverilog


pip3 install virtualenv requests
export PATH=$PATH:/home/$USER/.local/bin

mkdir ~/.virtualenvs && cd ~/.virtualenvs
python3 -m venv libresoc
sudo apt install python3.8-venv
source ~/.virtualenvs/libresoc/bin/activate

pwd
/home/santhosh/libresoc

git clone https://gitlab.com/nmigen/nmigen.git
git clone https://gitlab.com/nmigen/nmigen-boards.git

git clone https://gitlab.com/nmigen/nmigen-soc
cd nmigen
pip install wheel
python setup.py develop
cd../

cd nmigen-boards
python setup.py develop
cd../

cd nmigen-soc
python setup.py develop
cd../

Not available
#git clone https://gitlab.com/openpowerfoundation/openpower.git


git clone https://git.libre-soc.org/git/nmutil.git

git clone https://git.libre-soc.org/git/openpower-isa.git
cd openpower-isa; make develop; cd ..

git clone https://git.libre-soc.org/git/c4m-jtag.git

git clone https://git.libre-soc.org/git/ieee754fpu.git
git clone https://git.libre-soc.org/git/soc.git
cd ieee754fpu; make develop; cd ..

gmp.h file missing
apt-get install  libgmp3-dev

mpfr.h file missing
sudo apt-get install libmpc-dev 

Installing yosys
sudo apt-get install yosys


Ifconfig not found error
[[ -f /sbin/ifconfig ]] && echo "ifconfig exists"
echo $PATH
export PATH = $PATH:/sbin
----solved----

wifi driver run as sudo
apt update && apt install firmware-iwlwifi
sudo modprobe -r iwlwifi ;sudo modprobe iwlwifi






