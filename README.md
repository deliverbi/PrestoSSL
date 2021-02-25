# Presto SSL JDBC Driver with Unsigned Certificates and updated metadata fixes.
Presto SSL Driver with Unsigned Certificates

Have you been looking around like i was for a Presto SQL compatible driver that can be used for SSL and self signed certificates and unmatched host names..

When using remember to Set both the properties below to true for driver : presto-jdbc-deliverbi.jar

SSLAllowSelfSignedCert = true

SSL = true

Please find a compiled driver here within Github. Enjoy

************************2020/02/25 Update ***********************************

Their is also another driver uploaded PRESTO-DELIVERBI-JDBC-SSL . This driver has bug fixes for DBEAVER . Metadata is now loaded alot quicker over SSL and quicker in general as we have modified the way it collects metadata from Presto . Now its alot more efficient . 

Add 2 variables for SSL and unsigned certificates etc.

SSL = true

SSLVerification = NONE

When you setup Driver in dbeaver , after setting up connection and connecting once to dbeaver . Just restart Dbeaver once for driver to initialise


DELIVERBI team.
