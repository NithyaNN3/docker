- Each container has a different file system
- never store data in a container, store it in a volume

To create a volume, for example, run - docker run -d -p 5000:3000 -v app-data:/app/data <appname> after you make a directory > and rerun the image 
- when you create a file on /app/data and delete the image, the file doesn't get deleted. Volumes are the best way to persist data and can be shared across containers.
