Evolution-custom-htaccess
=========================

This one does NOT re-direct to burp or blackhole but sends HTTP response 403 (FORBIDDEN).
Security @ Line 1-7 and @ Line 57-141

+ @ Line 16 I uncommented:
php_value date.timezone ...

+ @ Line 19-20 I added: 
Options -Indexes
DirectoryIndex index.php index\.htm$l

http://forums.modx.com/thread/91891/is-it-a-hack?page=6#dis-post-506086
