It is a serverless module that lets you store webhook subscriptions and notify them of changes in your system.

**ETA - 2 weeks**

### Features:

- create a webhook
- post message to a webhook url
- retry posting failed messages with exponential back-off algorithm
- block webhook if url is no longer valid or resources has been moved
- delete a webhook

### Requirements:

- AWS account
- Serverless framework (specify the version)

### Running instructions:

- sls project init
- sls resources deploy
- sls function deploy
- sls endpoint deploy —all

### Examples:

- create a webhook
- delete a webhook
- pass on message to webhook module for delivery

### AWS Resources utilized:

- APIG - API urls facing the outside world
- Lambda - for computation
- SNS - for Lambda communication
- SQS - for storing failed messages
- DynamoDB - for storing webhook subscriptions

### Contributing
Contributions are always welcome!

### Credits
Developed by [microapps] (http://microapps.com/?utm_source=serverless-webhooks-readme&utm_medium=click&utm_campaign=github) Used in our live products: [MoonMail] (https://moonmail.io/?utm_source=serverless-webhooks-readme&utm_medium=click&utm_campaign=github) & [MONEI] (https://monei.net/?utm_source=serverless-webhooks-readme&utm_medium=click&utm_campaign=github)


## License
serverless-webhooks is available under the MIT license. See the LICENSE file for more info.
