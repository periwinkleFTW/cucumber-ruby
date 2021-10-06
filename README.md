# cucumber-ruby

# How to build: (-t means tag)

$ docker build -t <container_name> .

# Check if it is working

$ docker run -it --rm <container_name> ruby script.rb

# You need to build every time you add new code

# To run scripts you need to bash into the container

$ docker run -it --rm <container_name> bash
