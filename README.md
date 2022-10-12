# OIDC lambda helper for Amazon Cognito


The goal of this lambda is exchange a provided authorization code for the applation Id Token.

# Requirements

- AWS account and permissions to create CloudFromation stacks, Aws Secret Manager and lambda functions
- Nodejs and NPM

# Environment Variables

- ONEK_TENANT
- ONEK_COMMUNITY
- ONEK_CLIENTID
- ONEK_SECRET_NAME

# Deploy AWS Lambda

Please follow the official aws documentation:

- https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-awscli.html

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
