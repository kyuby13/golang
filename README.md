# golang
golang 
# Clone
git clone https://github.com/kyuby13/golang.git
# Build
docker build -t appgo:1.0 .
# run docker
docker run -d --name appgo -p 8000:8000 appgo:1.0
# Akses 
http://IPaddr:8000
