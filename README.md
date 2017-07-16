# FareCompare7Plus
Our FareCompare app that works specifically with the iphone 7+

To Generate New Lyft Access Token:

```
curl -X POST -H "Content-Type: application/json" \
     --user "Mdlycve9fovu:71nh2vP-aQwVzR4inI8b_dD6TSWucgei" \
     -d '{"grant_type": "client_credentials", "scope": "public"}' \
     'https://api.lyft.com/oauth/token'
```
