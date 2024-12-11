# kylacoin-miner
#env 
```linux```

#pool address: mpool.live

#minner tools
```https://github.com/doktor83/SRBMiner-Multi/releases```

#step to install
##update ubuntu
```
sudo apt update && apt upgrade -y
sudo apt install wget
```
##download tools
```
wget https://github.com/doktor83/SRBMiner-Multi/releases/download/2.7.2/SRBMiner-Multi-2-7-2-Linux.tar.gz
```
##untar file
```
tar -xvzf SRBMiner-Multi-2-7-2-Linux.tar.gz
```
##setup tool
```
cd SRBMiner-Multi-2-7-2/
```

#run 
```
./SRBMiner-MULTI --algorithm flex --pool stratum+ssl://asia.mpool.live:5213 --wallet kc1qvuts8xnw64z73qzxkl9qvw8tsqp95csdtrqqlv --password x --cpu-threads 0 --disable-gpu
```



