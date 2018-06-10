# FareCompare7Plus
Our app that lets you compare Uber and Lyft prices to find the cheapest route to your destination!

To Generate New Lyft Access Token:

```
curl -X POST -H "Content-Type: application/json" \
     --user "Mdlycve9fovu:71nh2vP-aQwVzR4inI8b_dD6TSWucgei" \
     -d '{"grant_type": "client_credentials", "scope": "public"}' \
     'https://api.lyft.com/oauth/token'
```
