This project is based on two container images which are (a)mysql:5.7 and (b)postfixadmin:latest.
For the above image you could download from https://hub.docker.com/ and search for the respectives image, or could download from the my repository i.e "docker push invincibleakshit/postfixadmin:tagname" and "docker push invincibleakshit/mysql:tagname".

docker-compose.yml uses invincibleakshit/postfixadmin image if you've downloaded official image kindly change the image name in the same file.
Required os:-
RehHat8,docker-ce and ,docker-compose.

command "docker-compose up -d"
After running this command run http://localhost:8080/setup.php
bydefault setup password is topsecret99

Note:- Downloading official postfiximage from docker hub and if warining occurs "Warning: Depends on: IMAP functions - NOT FOUND" then kindly use this link https://github.com/krufab/postfixadmin-docker/tree/bugfix/19-fix-imap-dependencies 
