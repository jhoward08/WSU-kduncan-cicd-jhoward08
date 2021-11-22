# Project_06 - CICD
----------------------------------
1. Get the Github repository.
* In Pilot, there is a link to go to. It looks like the one below:
![gitLink](Pictures/gitLink.jpg)
* Once attached to the repo, choose the medium in which the user will complete the website.
  I have chosen to use my first instance from lab_01 since WSL gives errors about docker.io.
2. Clone the NEW repo.
* Below is the screenshot from my repo clone.
![cloneCICD](Pictures/cloneCICD.jpg)
----------------------------------
3. Get Docker
* Now, one thing to do is to login to the instance which is self explanitory by now. Next the
  user will have to install docker and docker.io. Docker is the program and docker.io allows 
  the uplink to the docker repository for the images to download. . . (I THINK?!?).
![updateAndInstall](Pictures/updateAndInstall.jpg)
* It is always best to make sure that any executable or serivce is running after installation.
![dockerRunning](Pictures/dockerRunning.jpg)
----------------------------------
4. Get a webpage or splashpage
* Create a basic HTML file to replace the old "index.html" file that apache2 makes in "/var/www/html"
![simpleHTML](Pictures/simpleHTML.jpg)
----------------------------------
5. Pull an image
* From what I know about building an image, you usually need some type of base to lay the rest
  on. This is usually a OS like Ubuntu or a different flavor,
  ![dockerPull](Pictures/dockerPull.jpg)
* Now the DOCKERFILE. The dockerfile is basically a list of commands that will build the image
  of whatever you need the container to do.
