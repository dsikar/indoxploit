# indoxploit
Files I found on Wordpress installation related to vulnerabilities exploited by indoxploit.

## archive.php

Replaced original archive.php in wp-content/themes/simplicitybright/ (simplicitybright theme). This will list all files in Wordpress root directory, plus options to upload, delete and change file modes. 

## .htaccess

Redirects to news.php and file.php.

## htaccess.ss

Probably renamed, redirect to directory ss_slash_site_path.

## 404.php

Encoded html page, decoded with javascript unescape function. 

## 404-unencode.php

Unencoded 404.php using http://www.utilities-online.info/urlencode

