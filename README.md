## About
With these shell script and OpenSSL, you can create your own self-signed CA and sign your certificate with the CA. You can modify the config files to align your settings.

## Usage
1. Git or download & extract.
2. Modify the script and cnf files to align your settings.
3. Run *ar_root* to generate the CA (root certificate).
4. Run *ar_client* to generate the certificate signed with the CA.
5. Add the CA to OS trusted certificate pool, and it will makes all your client certificate be work and avoid any block/warning.

## Author && Contact
* Website: http://arlen.cn/
* Email: dev@arlen.cn
