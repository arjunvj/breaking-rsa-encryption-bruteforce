This program tries to calculate prime numbers p & q using distributed computing which determines phi and then decrypts the encrypted number by brute-force way.

To run:

cd Server
javac *.java
rmiregistry
java Server

cd ..
javac *.java
java Main [ip1] [ip2]