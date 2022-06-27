# convert-ssl

### Convert PEM to CRT

    openssl x509 -outform der -in your-cert.pem -out your-cert.crt
    
### Convert PEM to private

    openssl rsa -outform der -in private.pem -out private.key
