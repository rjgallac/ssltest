keytool -genkeypair -alias abc -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore abc.p12 -validity 3650

keytool -list  -v -keystore abc.p12