Deploying Static Websites in a Docker Container using an nginx webserver.

**1. Create HTML File.**


**2. Create 'Dockerfile'**



**3. Build Image Locally**

sudo docker build -t staticweb:1.0 .

**4. Run the container for webserver**
sudo docker run -d -p 8080:8080 --name staticwebserver staticweb:1.0 

**5. Check the output**
curl http://localhost:8080

Open in browser : http://localhost:8080
