nodejs-self-signed-certificate-example
=====

to make certificates for localhost


run
    sh make-root-ca-and-certificates localhost

you then need to copy the ca cert to your keychain , trust it and use the server cert on the server.
