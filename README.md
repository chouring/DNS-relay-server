# DNS-relay-server
DNS relay server implemented with language C.  

## what DNS-relay-servre do
Dns relay server is between the local server and remote dns server, it has three functions, the first one is to mask the some given domain names, the second is to cache the domain name that have been queried, the third one is to transmit the query to dns remote server and accept the back info, when local cache don't hit.

## how to start
Set the local default DNS to 127.0.0.1, close IPv6, and check whether the browser, nslookup, ping, etc. cannot be connected. After confirming that the DNS is invalid, run the program directly, and check whether the browser, nslookup, ping, etc. can be connected

## reference
RFC 1034 1035
