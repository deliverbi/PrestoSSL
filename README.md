# PrestoSSL with Unsigned Certificates and SSL
Presto SSL Driver with Unsigned Certificates

Have you been looking around like i was for a Presto SQL compatible driver that can be used for SSL and self signed certificates and unmatched host names..

When using remember to Set both the properties below to true

SSLAllowSelfSignedCert

SSL

Please find a compiled driver here within Github. Enjoy


Their is also another driver uploaded PRESTO-DELIVERBI-JDBC-SSL . This driver has bug fixes for DBEAVER . Metadata is now loaded alot quicker over SSL . 

Add 2 variables

SSL = true
SSLVerification = NONE

When you setup Driver in dbeaver , after setting up connection and connecting once to dbeaver . Just restart Dbeaver once for driver to initialise


DELIVERBI team.
