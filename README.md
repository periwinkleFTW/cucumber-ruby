# cucumber-ruby

# How to build: (-t means tag)

$ docker build -t <container_name> .

# How to run scripts:

-it is interactive mode that displays output to console/terminal
--rm removes container after exit

$ docker run -it --rm <container_name> ruby script.rb
