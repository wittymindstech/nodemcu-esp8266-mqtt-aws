# nodemcu-esp8266-mqtt-aws
sending data from nodemcu to aws using mqtt

# Create and download cretificates in original_certs  dir 

#install openssl

# Convert certifcicates to .der format using below commands

`openssl x509 -in 3c675stf21-certificate.pem.crt -out cert.der -outform DER`

`openssl rsa -in 3c675stf21-private.pem.key -out private.der -outform DER`

`openssl x509 -in AWSRootCA.pem -out ca.der -outform DER`


# copy all .der format files to data folder 

# Get the endpoint from AWS IoT core things and use in the code

