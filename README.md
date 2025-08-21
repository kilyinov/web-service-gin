docker buildx build --platform linux/arm64  -t albums-api .  
docker run -p 8080:8080 albums-api