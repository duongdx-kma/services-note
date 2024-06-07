- docker build -t node-app .

- docker run -p 9991:9999 --name nodejs1 -e APPID=nodejs1 -d node-app

- docker run -p 9992:9999 --name nodejs2 -e APPID=nodejs2 -d node-app

- docker run -p 9993:9999 --name nodejs3 -e APPID=nodejs3 -d node-app

* * * * * cd /var/www/html/taskebito/api && sudo php artisan schedule:run &>> /tmp/taskmiru.log
* * * * * cd /var/www/taskebito-api-tester && sudo php artisan schedule:run &>> /tmp/taskmiru-tester.log
