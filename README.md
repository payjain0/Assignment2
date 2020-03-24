Applied Cliend ID enforcement policy
client_id: 3f90f4ec560342e6ad95e783e6995124
client_secret: 71B98c1628df459c815c8aa72ADaa56b

#proxy url curl

curl --location --request GET 'http://practice-test-api-proxy.us-e2.cloudhub.io/hello' \
--header 'client_id: 3f90f4ec560342e6ad95e783e6995124' \
--header 'client_secret: 71B98c1628df459c815c8aa72ADaa56b'

#Implementation url curl

curl --location --request GET 'http://practice-test.us-e2.cloudhub.io/api/hello' \
--header 'client_id: 3f90f4ec560342e6ad95e783e6995124' \
--header 'client_secret: 71B98c1628df459c815c8aa72ADaa56b'




