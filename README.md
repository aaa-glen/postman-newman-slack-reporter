# newman-reporter-slackmsg

Takes test output of [Postman](https://www.postman.com/) / [Newman](https://github.com/postmanlabs/newman) reporter to send message to [Slack](https://slack.com/)

## Before you get started
- Install [Newman](https://github.com/postmanlabs/newman) ``` $ npm run i -g newman ```
- Create a [Slack incoming webhook url](https://api.slack.com/messaging/webhooks)

## Installation
 ```CLI
 npm i -g newman-reporter-slackmsg
 ```

## Usage
 ```CLI
 newman run <collectionFile> -e <environmentFile> --suppress-exit-code -r slackmsg --reporter-slackmsg-webhookurl '<webhookurl>'
 ```