# Certificates
Public certificates of KargWare and N13.org.

## Public Domains
* [kargware.de](https://kargware.de)
* [kargware.com](https://kargware.com)
* [kargware.info](https://kargware.info)
* [kargware.net](https://kargware.net)
* [kargware.org](https://kargware.org)
* [n13.org](https://n13.org)

## Local Domains
* kargware.lan, kargware.local
* n13.lan

## Subject of certificates

|Key|Description|Example|KargWare|N13|
|---|---|---|---|---|
|CN|commonName|"CN=My Root CA"|KargWare CA| n13.org CA|
|E|email|"E=office@company.com"|---|---|
|OU|organizationalUnitName|"OU=Dev"|Engineering|Open Source Development|
|O|organizationName|"O=Company Ltd"|KargWare|n13.org|
|L|localityName|"L=San Francisco"|Dingolfing|Dingolfing|
|S|stateOrProvinceName|"S=CA"|Bayern|Bayern|
|C|countryName|"C=US"|DE|DE|
|STREET|street with no|"STREET=Main Road 1"|---|---|
|PostalCode|zip or postal code|"PostalCode=12345"|84130|84130|

Example of whole subject
```
"CN=My Root CA,E=E=office@company.com,O=Company Ltd,L=San Francisco,S=CA,C=US,STREET=Main Road 1,PostalCode=12345"
```
