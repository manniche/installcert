installcert
===========

InstallCert is used to create a java keystore containing website
certificates, to use in java applications that need to communicate
securely with webservices or websites.

Building
--------

`mvn clean package`

Running
-------
from the root of the folder:

`java -jar -cp target/classes java com.aw.ad.util.InstallCert hostname`
