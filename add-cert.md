# Add cert to JVM
su - danielco-ca -c "sudo /Library/Java/JavaVirtualMachines/temurin-8.jdk/Contents/Home/jre/bin/keytool -import -alias vault-localhost -keystore /Library/Java/JavaVirtualMachines/temurin-8.jdk/Contents/Home/jre/lib/security/cacerts -storepass changeit -file /tmp/vault.cert -trustcacerts"

