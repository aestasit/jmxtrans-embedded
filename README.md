# jmxtrans embedded in a WAR

This project simply packages `jmxtrans` dependencies and logging configuration into a WAR application. It should be possible to deploy this WAR to any J2EE container. Upon deployment, application expects `jmxtrans.json` to be present in the container's working directory. All logs will be redirected to `/var/log/jmxtrans.log` file.