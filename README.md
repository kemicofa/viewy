# Viewy

Viewy is a blazingly fast microserivce that counts views built with rust.

:construction: Under Construction :construction:


## Scheme of a Viewy URL


Sending view:
```
http://viewy.rs/{apikey}/{domain}/{uuid}/{pid}
```

## Specifications

A "view" can be defined as accessing a specific piece of information by a user or 
re-visiting user outside a period of time.

A "user" is recognized through a UUID (unique user identifier)

## F.A.Q.

### Why a microservice to count views?

Counting views is not as simple as adding +1 every time a user sees a web page.
