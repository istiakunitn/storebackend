# Simple application to create Stripe payment intent
This application is for practise purpose and it only create a payment intent on stripe. 

## Dependency

`go 1.23.4` is used

## How to run?

Clone the app and just run `go run server.go`

The app will listen on `localhost:4242`

You can send a post request in endpoint `/create-payment-intent` and it will return

```
{
  "clientSecret": "payment_intent_id"
}
```