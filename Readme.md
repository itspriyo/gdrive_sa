#  Google Service Account Tutorial Commands:

Termux Command -
```
termux-setup-storage
```
```
pkg update
```
```
pkg upgrade 
```
```
pkg install git
```
```
pkg install python
```
```
pip install --upgrade pip
```
```
mkdir /sdcard/MyTermux/ -p
```
```
cd /sdcard/MyTermux
```
```
git clone https://github.com/itspriyo/gdrive_sa
```
```
cd /sdcard/gdrive_sa/service-accounts
```
```
pip3 install -r requirements.txt
```
credentials.json file [Google Console](https://console.cloud.google.com/?pli=1)

```
python3 gen_sa_accounts.py --quick-setup -1
```
```
python3 gen_sa_accounts.py  --download-keys Project ID
```
[`Project ID​`](#) Project ID

```
python generate_drive_token.py
```
```
cd accounts
```
```
python3 emails.py
```
