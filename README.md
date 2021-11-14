## React app Dockerized

It is a simple react app. I created this project with the command:

  $npx create-react-app react-docker
  
After, I create a Dockerfile to specify instructions needed to create the corresponding image.

You can have the image by writing this command :
   
   $docker pull nourchen/react-docker:1
  
  
## Run the container

In your terminal, as a root user, write:

  $docker run -d -p 8080:3000 nourchen/react-docker:1
  
  
In you browser, you can check : http://localhost:8080/  and you see the react application up and running.
  
