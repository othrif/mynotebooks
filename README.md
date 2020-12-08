# mynotebooks

### Build and run docker image
``` bash 
docker build -t othrif/recordme:v1 .
docker run -p 8888:8888 --name test othrif/recordme:v1
```


### Pull and run docker image
``` bash
docker pull othrif/recordme:v1
docker run -p 8888:8888 --name test othrif/recordme:v1
```