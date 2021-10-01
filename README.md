

 docker build --rm -f Dockerfile -t shwks-nginx:latest .

docker run --rm -d -p 80:80 shwks-nginx:latest