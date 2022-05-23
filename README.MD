# Flask API 

This source contains Flask API application and Docker file

### Building docker image 
```
git clone https://github.com/Ssharukh007/Flask-API.git

cd Flask-API

docker build -t flask_image:Version1 .

```
### Running the Docker container

```
docker run -d --name python_flask_new -p 5000:5000 flask_image:Version1

```
### Command to check application

```
curl http://localhost:5000/

#This can be browsable using Host IP istead of localhost , e:g http://54.173.156.239:5000
```
