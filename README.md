# Setup
Requirements
Install node version 14+ 
Install docker for create image

# Running node application
1. Checkout code from master branch
2. For install node modules `npm install`
3. For running the application `npm start`
 
# Create docker image and run
1. Create Dockerfile in root folder of the application
2. For creating image run below command
      `docker build -t myapp .`
3. Run the image
       `docker run -p 8080:3000 -d myapp`
       
