### Para construir:

``sh docker-debian.sh``

### Para executsar o container:

``
docker run -it -p 1880:1880 -v nr-data:/data --name smart40 smart40:node-red-build
``