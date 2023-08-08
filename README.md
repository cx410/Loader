Clone
```
$ git clone https://github.com/cx410/Loader.git
```
Folder
```
$ cd Loader
````
config
```
$ mv config.env.sample config.env
```
Build
```
$ docker build . -t userge
```
Run
```
$ docker run -d --restart on-failure --name userge_1 userge
```
Log
```
$ docker logs userge_1
```
