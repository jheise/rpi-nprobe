# rpi-nprobe

Run nprobe on a raspberry pi in docker

`docker run -d -p 2055:2055/udp -p 9996:9996/udp jheise/rpi-ntopng`

nprobe will collect netflow data and make it available via zeromq
