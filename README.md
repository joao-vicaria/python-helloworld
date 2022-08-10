# python-helloworld
# Simple Instructions to HowTo build the container image

1 - Download Repository:

   `git clone https://github.com/joao-vicaria/python-helloworld.git`

2 - Go into to the directory python-helloworld:

   `cd python-helloworld`

3 - Build image:

   `docker build -t <image_name> .`

4 - Run Container:

   `docker run -p 5000:5000 <image_name>`
