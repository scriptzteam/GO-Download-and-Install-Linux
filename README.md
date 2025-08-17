# GO-Download-and-Install-Linux
Download and install Go quickly with the steps described here.

```
wget https://go.dev/dl/go.1.25.linux-amd64.tar.gz
rm -rf /usr/local/go && tar -C /usr/local -xzf go.1.25.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go version
```
