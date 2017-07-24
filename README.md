# getiplayer docker

creates a docker with get_iplayer and the get_iplayer.cgi web interface, with the web interface hosted on apache

i followed the instructions from https://squarepenguin.co.uk/wiki/wpmdoc/


#Example Docker command

Host machine directory /home/ben/output
Host machine port 8185

docker run --name giplayer1 -v /home/bentech/output:/var/www/html/get_iplayer/output -p8185:80 mnbf9rca/getiplayer
