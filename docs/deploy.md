# Deploy

Is this your first deploy?  An incremental deploy?  SAS 9 or Viya?


## Viya Deploy

The standard location of the static content area on the Viya web server is `/var/www/html`.

If this isn't right you can take the following advice courtesy of Kurt Bremser in this communities [thread](https://communities.sas.com/t5/Developers/How-do-I-locate-the-static-content-area-of-the-web-server-on/m-p/589385):

```
Check if httpd uses a special config file (display the command line with ps -f).

If not, simply search for httpd.conf. Within that, you find the location of DocumentRoot.
```