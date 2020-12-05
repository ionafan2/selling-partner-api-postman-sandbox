# Selling Partner API Postman Sandbox
Postman Collection to lunch&play with Amazon Selling Partner API. \
Feel free to contribute to this repo!

## Requirements
- [Postman](https://www.postman.com/)

## How to run?
- Import collection to Postman
- Follow [Self Authorization](https://github.com/amzn/selling-partner-api-docs/blob/main/guides/developer-guide/SellingPartnerApiDeveloperGuide.md#self-authorization) and receive `refresh_token`
- __Edit collection's variables__
- Create new Environment like: `SP Api Env`
- Run `Init` folder to `assumeRole` get `accessToken` using `SP Api Env` Environment to set up Env variables
- Run `ApiCalls` using `SP Api Env` Environment

## Troubleshooting
- AccessToken last only one hour, then you should Run `Init` folder to refresh it
