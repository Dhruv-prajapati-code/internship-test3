

# Image vs Container vs Volume vs Network

Image  
It is a blueprint for creating containers.  it have application code, libraries, dependencies, and environment settings. 

Container  
A running environment of an image. Provides execution of applications with their dependencies.  

Volume  
A persistent data storage in Docker.    
Example: -v mydata:/var/lib/mysql.  

Network  
A communication path between containers.  



# Cleaning Up Unused Docker Resources

We use these commands:
docker container prune
docker system prune -a

# Best Practices for Writing Secure Dockerfiles
Use official base images like slim and alpine for only required dependency
Run as non-root user
Minimize size
Use .dockerignore
