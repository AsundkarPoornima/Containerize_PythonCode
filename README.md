# Containerize_PythonCode
#To create the image from Dockerfile
docker build -t mycodepy .
#To create Container and Outputfile
docker run mycodepy > output.txt
#To view the Python Output
cat output.txt

