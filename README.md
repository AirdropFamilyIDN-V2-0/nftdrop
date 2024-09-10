# NFT DROP MULTI AKUN
# HOW TO RUN
```
git clone https://github.com/AirdropFamilyIDN-V2-0/nftdrop.git
```
```
cd nftdrop
```
```
python config.py
```
```
python nftdropmulti.py
```
# Input pvkeylist dengan privatekeymu
- pvkey1
- pvkey2
- pvkey3
- pvkey4

# How To Install Requirements
# For Windows
- [Download Here](https://www.python.org/downloads/release/python-3100/)
- Recomended Using Python 3.10
- Maybe For Windows 10 Or Higher You Can Install Python 3.10 From Microsoft Store
```
python -m pip install pip --upgrade
pip install requests
pip install web3==6.20.1
pip install schedule
pip install pytz
```
# For Termux Android
- [Download Here](https://f-droid.org/repo/com.termux_1020.apk) [F-Droid Version]
- After Install Termux, Make Sure Allowed Permission Storage On Setting Termux
```
pkg update && upgrade
pkg install tur-repo
pkg install python-is-python3.10
pip install --upgrade pip
pkg install -y rust binutils
CARGO_BUILD_TARGET="$(rustc -Vv | grep "host" | awk '{print $2}')" pip install maturin
pip install requests
pip install web3==6.20.1
pip install schedule
pip install pytz
```
# For Ubuntu 18.04 | 20.04 | 22.04 (VPS)
```
apt update && sudo apt upgrade -y
apt install software-properties-common -y
add-apt-repository ppa:deadsnakes/ppa
apt install python3.10
apt install python3-pip
pip install requests
pip install web3==6.20.1
pip install schedule
pip install pytz
```
