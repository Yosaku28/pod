# test
```
docker start ub
docker exec -it ub bash
apt update
apt install python3-pip
pip3 install mecab-python3
pip3 install gensim
apt -y install mecab mecab-ipadic-utf8
apt-get install p7zip-full
mecab -Owakati 2002.txt -o 2002_wakati.txt
apt-get install nkf
nkf -w --overwrite 2002_wakati.txt
```