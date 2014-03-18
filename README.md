zabbix-java-tomcat
==================

This Repository is installing Zabbix Template with Tomcat 7 monitoring settings.

How To Use
----------

* template_jmx_general_with_username_and_password.xml

This template is customized from Zabbix 2.2 original template named [Template JMX General].
Template JMX General is blank in JMX username and password.
So I set Zabbix macro in this template.
To use this template you should input Only two macro in host using this tmeplate.
See below sample.

```
{$JXM_USERNAME} jmx_username
{$JXM_PASSWORD} jmx_password
```
