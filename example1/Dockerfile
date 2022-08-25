# dockerfile (blueprint for building images) , image(template for running containers) , container (running process for ur app)
FROM python:3.9

# add our file into a container 
ADD main.py . 

#install the third party libraries
RUN pip install requests beautifulsoup4

# cmd that will be executed when the container is started 
CMD ["python", "./main.py"]
#know we w'll build our docker image : cmd : docker build -t python-imdb .
# and know we w'll run our docker image : cmd : docker run python-imdb
