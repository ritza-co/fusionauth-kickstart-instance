# Kickstart a FusionAuth instance

This repository has configuration files to allow you to quickily start a FusionAuth instance using Docker.

## Project Contents

The `docker-compose.yml` file and the `kickstart` directory are used to start and configure a local FusionAuth server. The `.env` file contains the environment variables used by the FusionAuth instance.


## Running FusionAuth

To start FusionAuth run the following command 

```
docker compose up
```

This will start a PostgreSQL and FusionAuth server

FusionAuth will initially be configured with these settings:

* Your client id is: `e9fdb985-9173-4e01-9d73-ac2d60d1dc8e`
* Your client secret is: `super-secret-secret-that-should-be-regenerated-for-production`
* Your example username is `richard@example.com` and your password is `password`.
* Your admin username is `admin@example.com` and your password is `password`.
* Your API key is `33052c8a-c283-4e96-9d2a-eb1215c69f8f-not-for-prod`
* Your fusionAuthBaseUrl is 'http://localhost:9011/'
