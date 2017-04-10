# Retro Dungeon Crawler

# Environment Set

1. Open  terminal and enter command:
```sh
cd /etc/apache2
open .
```
2. A window will open, and open `httpd.conf` in a text editor.
3. Search for `AddHandler cgi-script .cgi`and remove the hastag in front of it. Do the same for `AddType text/html .shtml` and `AddOutputFilter INCLUDES .shtml`.
4. Save the file, it will probably ask you to put in your password, so so do it.
5. You macbook can now read CGI files, hopefully.

[Source](http://www.cgi101.com/book/connect/mac.html)

# Start/Stop Server
1. In a terminal, enter command:
```sh
sudo apachectl start
```
2. In a browser, navigate to `localhost`, you should see "It Works" appear.
3. To stop server, enter command:
```sh
sudo apachectl stop
```


# Access html files
```sh
open /Library/WebServer/Documents
```