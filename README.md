# Lock_dir
Encrypt and decrypt directories using 2 bash scripts

First the script 'lock' compresses the dir to a .tar thereafter encrypts it using mcrypt, and
finally deletes the initial dir and .tar only leaving the encrypted *.tar.nc

Second the script 'unlock' decrypts the .tar thereafter extracts it, and finally deletes
the initial .tar.nc and .tar only leavoing the initial dir.
