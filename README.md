Usage
Install
Pull sona/sona from the Docker repository:

docker pull sona/sona
Or build sona/sona from source:

git clone [https://github.com/sona/dockerfile.git](https://github.com/iamsonna/Docker-Zero)
cd dockerfile
docker build -t sona/sona .
Run
Run the image, binding associated ports, and mounting the present working directory:

docker run -p 9778:9778 -v $(pwd):/app:rw sona/sona help
Append the sona command to the end of your docker run command.
The above example uses help.
