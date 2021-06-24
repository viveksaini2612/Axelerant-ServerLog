# Axelerant-ServerLog
#Install apache server and start services

![apache server](https://user-images.githubusercontent.com/51254973/123253129-be0f6000-d50a-11eb-8016-321983c32f26.PNG)

 # List the top 5 unique IP addresses accessing your Apache webserver
 go to file /var/log/http/access_log     
 # awk '{ print $1}' access.log.2021-06-24 | sort | uniq -c | sort -nr | head -n 5
 
# List the past 10-days 4XX results of Apache's access log file, sorted by date with their IP address
