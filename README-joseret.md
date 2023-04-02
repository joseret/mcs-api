```
cd ~/sw
wget https://go.dev/dl/go1.18.10.linux-amd64.tar.gz
mkdir -p ~/sw.go1.18.10
tar -C ~/sw/go1.18.10 -xzf go1.18.10.linux-amd64.tar.gz
export PATH=$HOME/sw/go1.18.10/go/bin:$PATH
```