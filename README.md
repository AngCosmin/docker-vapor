# Docker Vapor Swift

1. Create a folder. For example `D:/Vapor`
2. Download `Dockerfile` and put it inside `D:/Vapor`
3. Open a command prompt
4. Run `docker build -t myvapor .`
5. Run `docker run --rm -it -v D:/Vapor:/app -p 8080:8080 myvapor`
6. Create a new project inside the container `vapor new HelloWorld`
7. Build the project `cd HelloWorld` and `vapor build`
8. Run the service `vapor run serve --hostname=0.0.0.0`
9. Navigate to `http://localhost:8080`
10. Profit

## Note

For Windows PATH use `/` not `\`
