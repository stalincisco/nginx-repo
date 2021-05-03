# install Nginx

          $ ./configure
          $ apt-get install nginx
          $ kubectl get pod --all-namespaces
          $ kubectl get nodes
          $ history
          $ ps aux | grep nginx (to see if nginx process is running) 
          
### Open Vscode in Superusermode
    
          $sudo code --user-data-dir="~/.vscode-root"

## go to nginx.org and get the latest version of nginx and install 

          $ wget http://nginx.org/download/nginx-1.19.10.tar.gz
          $ tar -zxvf nginx-1.19.10.tar.gz
          $ ls
          $ clear
          $ ls
          $ cd nginx-1.19.10
          $ ls
          $ ./configure
          $ apt-get install build-essential
          $ clear
          $ ./configure

          $ apt-get install libpcre3 libpcre3-dev zlib1g zlib1g-dev libssl-dev

          $ ./configure
          $ ./configure --help

## Configure nginx from the source with ssl module 
 
          $ ./configure --sbin-path=/usr/bin/nginx --conf-path=/usr/bin/nginx/nginx.conf --error-log-path=/var/log/nginx/error.log --http-log-path=/var/log/nginx/access.log --with-pcre --pid-path=/var/run/ngnix.pid --with-http_ssl_module
              $ ls -l /etc/nginx/
              $ nginx -v (for version of nginx)
              $ nginx ( to start nginx) 
              $ cd ..
              $ ls
              $ ps aux | grep nginx
              $ systemctl stop nginx ( to start nginx) 
              $ systemctl enable nginx ( to enable nginx even after reboot of the server) 
              $ history

## Configure Project demo

              $ systemctl restart nginx ( to stop and restart nginx) 
              $ systemctl reload nginx ( to reload the nginx) 
              $ nginx -t (to verfy is the configuration file is okay)
    
### write the same content of the file in git (01+Creating+a+Virtual+Host.conf) to /etc/nginx/nginx.conf

              $ curl -I http://192.168.1.21/style.css  (to check if mime type is text/css)
              $ systemctl reload nginx ( to reload the nginx) 
    
## Location Blocks 
    
    
    
