## Local project bootstrap

```sh
mkdir project
cd project
git init
git clone <repo_url>        # alternative to init
```

## File and permission prep

```sh
chmod +x script.sh
chmod 400 id_rsa             # SSH key
```

## Virtual environments (Python example)

```sh
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Node setup

```sh
npm init -y
npm install
```

## SSH connection

```sh
ssh -i id_rsa user@host
```

## Remote project pull

```sh
git clone <repo_url>
cd repo
git pull origin main
```

## Remote environment prep

```sh
sudo apt update && sudo apt install -y build-essential git
python3 -m venv venv
source venv/bin/activate
```

## File transfer

```sh
scp -i id_rsa localfile user@host:/path/
scp -i id_rsa user@host:/path/remotefile .
```

## Process inspection and control

```sh
ps aux | grep process
sudo systemctl status servicename
sudo systemctl restart servicename
```

## Basic directory operations

```sh
ls -la
mkdir -p src
mv fileA fileB
rm -rf build/
```
