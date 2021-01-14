# evenOdd
[![Build Status](http://labpsrv-00.francecentral.cloudapp.azure.com:8080/buildStatus/icon?job=even-odd-pipeline)](http://labpsrv-00.francecentral.cloudapp.azure.com:8080/job/even-odd-pipeline/)

Należy dodać shared library do Jenkins jako 'evenOdd'.

Przejdź do 'Zarządzaj Jenkinsem' -> 'Skonfiguruj system' -> 'Global Pipeline Libraries'
Następnie 'Dodaj':
* Name: evenOdd
* Default version: master
* Load implicit: v
* SCM Git: https://github.com/r3dl0ck/evenOdd.git
