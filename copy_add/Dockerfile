FROM ubuntu
WORKDIR /files

# home/files/image_file.txt
COPY host_file.txt image_file.txt

# home/files/image/path/image_file.txt
COPY host_file.txt image/path/image_file.txt

# home/image_file.txt
COPY host_file.txt /image_file.txt

#download from web
ADD http://google.com/robots.txt robots.txt
# decompress
ADD zyps.tar.gz zyps/