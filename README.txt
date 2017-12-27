


To build this container from scratch:
 
git clone https://github.com/kmullins/dockerwebclient.git
cd dockerwebclient
sudo docker build -t "yourreponame:yourimagename" .
	example:    sudo docker build -t "kmmmullins:kmweb" .
sudo docker run --name kmweb -d -p 80:80 kmmmullins:kmweb
sudo docker exec -it kmweb /bin/bash


kmmmullins@gmail.com
 

