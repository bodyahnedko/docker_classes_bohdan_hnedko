docker build -t docker-nginx <br/>
docker run -it --rm -d -p 8080:80 --name web docker-nginx <br/>
Go to the browser and open http://localhost:8080 <br/>