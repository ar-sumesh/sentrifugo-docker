# sentrifugo-docker
## How to start using this sentrifugo docker
* Clone this repository in your system
``` 
$ git clone https://github.com/ar-sumesh/sentrifugo-docker.git
```
* Go inside this directory and run following commands
```
$ cd sentrifugo-docker

$ docker-compose up -d

```
* also check logs if everything is working fine
```
$ docker-compose logs -f
```
## How to access the website

* open any browser in your system and search for <code>http://localhost/sentrifugo/</code>.
* You can also change <code>localhost</code> with your system's IP address. 
* After you access the website then you see **Database settings** in **left panel** put following configuration there:
```
HOST -> db
DATABASE USER -> root
DATABASE USER_PASSWORD -> root
DATABASE NAME -> sentrifugo
```