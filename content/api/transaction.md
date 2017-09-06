Khalti provides API for retrieving list of payments made to a merchant.
A merchant should use secret test and live keys for retrieving test and live payments respectively.

## List payments
```curl
curl https://khalti.com/api/transaction/ \
   -H "Authorization:Key <secret key>
```

## Retrieve a payment
```curl
curl https://khalti.com/api/transaction/<idx>/ \
   -H "Authorization:Key <secret key>
```
