ARG centos=7.9.2009
FROM aursu/php73build:${centos}-build

RUN yum -y --enablerepo=bintray-php73custom install \
        php-pear \
    && yum clean all && rm -rf /var/cache/yum /var/cache/dnf
