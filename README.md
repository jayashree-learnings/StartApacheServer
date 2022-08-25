# StartApacheServer


1)create a folder with  approprite name ProjApacheStart

2)Navigate to the folder using cd command.
3)Use vi or vim  to create a file "ApacheStart.sh " containing the following commands
      #!/bin/bashpr
      
      sudo apk update 
      apk add apache2
      mkdir -p /run/apache2 
      /usr/sbin/httpd
4)Run the script using sh ApacheStart.sh
5)Verify the server is up and running by connecting with it via no:80
6)If everything is fine, it displays the "It Works"  page.




