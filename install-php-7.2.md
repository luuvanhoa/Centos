https://www.cyberciti.biz/faq/how-to-install-php-7-2-on-centos-7-rhel-7/

How to install PHP 7.2 on RHEL 7
The steps are as follows to enable and install PHP 7.2 on RHEL 7 using yum command:
$ sudo yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
$ sudo yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm
$ sudo yum install yum-utils
$ sudo subscription-manager repos --enable=rhel-7-server-optional-rpms
$ sudo yum-config-manager --enable remi-php72
$ sudo yum update
$ sudo yum search php72 | more
$ sudo yum install php72 php72-php-fpm php72-php-gd php72-php-json php72-php-mbstring php72-php-mysqlnd php72-php-xml php72-php-xmlrpc php72-php-opcache