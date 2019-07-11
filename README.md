# Panda
This is an PHP environmental management gadget.

~~~~phpize
php安装路径/bin/phpize
./configure --with-php-config=php安装路径/bin/php-config
make && make install

php.ini
extension=Panda.so

[Panda]
panda.environ=local
demo:
$a = Environ();
var_dump($a);~~~~
