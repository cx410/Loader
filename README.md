Update
```
apt-get update
```
Pip
```
apt install python3-pip
```
Clone
```
git clone https://github.com/cx410/Loader.git
```
Folder
```
cd Loader
````
Config
```
mv config.env.sample config.env
```
Edit config
```
nano config.env
```
Build
```
docker build . -t userge
```
Run
```
docker run -d --restart on-failure --name userge_1 userge
```
Log
```
docker logs userge_1
```
