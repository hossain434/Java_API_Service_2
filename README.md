# Java_API_Service_2

1. Java API: https://docs.oracle.com/javase/8/docs/api/
2. Install Apache 8: 32-bit/64-bit Windows Service Installer
3. Confuguration: Server Shutdown port: 8005, Connection port: 8080
4. If tomcat doesn't start then delete the server and re-create. Eclipse: Window->Show View->Servers
5. Multiple Apps can be run under same tomcat.
6. Tomcat can be run either inside of eclipse or outside. Just toggle tomcat server location either use workspace or use tomcat installation. then restart tomcat server. See: https://crunchify.com/tomcat-starts-but-home-page-does-not-open-on-browser-with-url-http-localhost8080/
7. On console- Right click on servers tab->Properties->General-> make sure location always be /server/tomcat8.5 at localhost, if this is not then switch location to this.
8. Deploy war file to tomcat: do maven build..(dot dot), set parameter clean install, war file will create in target folder.
9. login: http://localhost:8080/, ->Manage app->deploy war file. App will run after close the eclipse. just goto tomcat bin folder, click startup bat file.


Reference:
https://crunchify.com/how-to-build-restful-service-with-java-using-jax-rs-and-jersey/
