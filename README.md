Required Commands

step 1: docker-machine create --driver virtualbox Char:
        how to create a virtual machine with docker-machine
        using the virtualbox driver

step 2: docker-machine ip Char:           
        how to get the IP address of the Char virtual machine.

step 3: eval $(docker-machine env Char) 
        how to define the variables needed by your virtual machine
        Char in the general env of yourterminal, 
        so that you can run the docker ps command without errors.

step 4: docker pull hello-world:
        how to get the hello-world container from the Docker Hub, 
        where it’s available.
        
step 5: docker run hello-world:
        Launch the hello-world container, 
        and make sure that it prints its welcome message,
        then leaves it.
step 6:
        how do you go about Launching an nginx container, available on Docker Hub, as a background task. It
        should be named overlord, be able to restart on its own, and have its 80 port
        attached to the 5000 port of Char. You can check that your container functions
        properly by visiting
        http://<ip-de-char>:5000 on your web browser
