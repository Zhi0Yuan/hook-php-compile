http://php-security.org/2010/05/13/article-decoding-a-user-space-encoded-php-script/index.html

phpize && ./configure && make

php -d extension=evalhook.so encoded_script.php

添加了对`zend_compile_file()`的hook
