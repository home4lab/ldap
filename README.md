# ldap

apt install slapd ldap-utils
dpkg-reconfigure slapd


apt install phpldapadmin


# change 127.0.0.1 to your_ip
$servers->setValue('server','host','127.0.0.1');

**change to your domain**
$servers->setValue('server','base',array('dc=example,dc=com'));

**change to your domain**
$servers->setValue('login','bind_id','cn=admin,dc=example,dc=com');


**uncomment this and set to true**
// $config->custom->appearance['hide_template_warning'] = false;
