# Ride: Geocode

Integration of the geocode library with a Ride application.

## Related Modules 

- [ride/app](https://github.com/all-ride/ride-app)
- [ride/lib-geocode](https://github.com/all-ride/ride-lib-geocode)

## Installation

You can use [Composer](http://getcomposer.org) to install this application.

```
composer require ride/app-geocode
```


## Usage

If you want to use the Google geocode service, you will need to add a ```google.geocode.key```.

You will need to create this key on  console.developers.google.com and restrict it for the specific api's you want this key to be used.

Preferable you will only use this for geocoding and nothing else, since the key can't be publicly visible (no referer restrictions are allowas on the Geocode API).