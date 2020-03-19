# MCSV

/opt/MCSV



/etc/supervisor/conf.d

tail -f /var/log/supervisor/supervisord.log


sudo /etc/init.d/supervisor stop

sudo /etc/init.d/supervisor start

sudo java -Xmx1024M -Xms1024M -jar /opt/MCSV/server.jar nogui



netstat -putan | grep LISTEN
ps aux | grep java

