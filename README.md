# passboat-manager

This tool is used to manage password 

Documentation and guide Links:-

Install Guide 
https://www.passbolt.com/docs/hosting/install/ce/docker/

Toturial  
https://youtu.be/jAfQvMxcokI?si=N-oxyFua1UEzhrhW

https://www.passbolt.com/docs/hosting/configure/https/ce/docker-auto/

Run Command -------------------------------------------   

docker-compose -f docker-compose-ce.yaml up -d

docker-compose -f docker-compose-ce.yaml exec passbolt su -m -c "/usr/share/php/passbolt/bin/cake passbolt register_user -u hemantrajput6969@gmail.com -f hemant -l rajput -r admin" -s /bin/sh www-data
