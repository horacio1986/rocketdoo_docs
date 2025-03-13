# Command Line

Know the most common commands you can use in **ROCKETDOO**.

* With this command you start the framework.

~~~
rocketdoo
~~~

* To raise the environment once the launcher is finished.

~~~
docker compose up
~~~

Then with this variant you can deploy the environment without seeing the log result in the terminal.

~~~
docker compose up -d
~~~

* How to get the *sudo* permissions in docker.

~~~
sudo groupadd docker
~~~

~~~
sudo usermod -aG docker $USER
~~~

With this you should be able to run docker without sudo.

If it doesn't work you can try these commands.

~~~
sudo newgrp docker
sudo usermod -aG docker $USER
~~~

* Pause containers.

~~~
docker compose pause
~~~

* Unpause containers.

~~~
docker compose unpause
~~~

* Brake the containers.

~~~
docker compose stop
~~~

* Pause or brake a particular container.

~~~
docker container pause <container-name> 
docker container stop <container-name>
~~~

* Re-initialize containers.

~~~
docker compose restart
~~~

* Delete containers.

~~~
docker compose down
~~~

* Remove the containers with their volumes.

~~~
docker compose down -v
~~~

* Force a rebuild of your environment.

~~~
docker compose up --build
~~~

* Know the status of your containers.

~~~
docker compose ps
~~~

* List the images constructed.

~~~
docker image ls
~~~

* Delete an image.

~~~
docker rmi <image-name>
~~~

* Clean your PC of images and content that you no longer use in docker.

~~~
docker system prune
~~~

* Massively update module packages loaded as public repositories with Gitman.
Gitman.

This must be done inside the container.

~~~
gitman update
~~~

