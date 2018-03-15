# geocoder-front
Front-end of the Historical Geocoder.

For PHP, you need the following package: php-pgsql php-xml

In order to be able to run the front-end, you need to set the following environment variables :
- GEOCODER_PG_HOST
- GEOCODER_PG_PORT
- GEOCODER_PG_DBNAME
- GEOCODER_PG_USER
- GEOCODER_PG_PASSWORD

These variables allow the frontend to connect with the postgresql database containing the geohistoricaldata
