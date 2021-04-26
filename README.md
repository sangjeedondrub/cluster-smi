# cluster-smi

> `nvidia-smi` but for cluster ➝ `cluster-smi`
>
> A fork of https://github.com/PatWie/cluster-smi

# Install system dependencies

```
sudo apt install libzmq3-dev
```

# Install `cluster-smi`

```
cd $GOPATH/src/github.com

git clone https://github.com/sangjeedondrub/cluster-smi

cd cluster-smi

cp -rf config.example config.go

# change your configuration, if it is required,
# e.g. `c.RouterIp = "****"`

go get

make
sudo make install
sudo make install-router
```

# Credit

All credit goes to `https://github.com/PatWie`
