# strapi-provider-upload-minio

## Installation and basic usage

`cd [your-strapi-project]`

`npm install --save strapi-provider-upload-minio`

start your strapi application and go to: plugins => files upload settings

from the providers list select **Minio Server**

fill in:

- access token (ex: Q3AM3UQ867SPQQA43P2F)
- secret token (ex: zuf+tfteSlswRu7BJ86wekitnifILbZam1KYY3TG)
- endpoint (ex: https://play.minio.io:9000)
- bucket (_must exist on your minio server_)

NOTE: bucket policy must be set to allow your file to be readable. (just set it to: prefix \*, readonly)

## Resources

- [MIT License](LICENSE.md)

## Links

- [Strapi website](http://strapi.io/)
- [Strapi community on Slack](http://slack.strapi.io)
- [Strapi news on Twitter](https://twitter.com/strapijs)
