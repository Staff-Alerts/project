# DEFRA DEV

- Tools
    - Most devs use VS Code as their code editor
        - [Standard JS Plugin](https://marketplace.visualstudio.com/items?itemName=chenxsan.vscode-standardjs)
    - [StandardJS](https://standardjs.com/) should be used to lint/format code. Install the VS code plugin to get editor feedback of formatting errors.
- Libraries/Frameworks
    - [hapi.js](https://hapi.dev/) is the web framework used for nodejs applications across defra
    - [GovUK Design System](https://design-system.service.gov.uk/)
    - [Nodejs AWS SDK](https://aws.amazon.com/sdk-for-node-js/) and docs [here](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/index.html)
    - [Twilio](https://www.twilio.com/)
- Examples
    - XWS
        - [XWS](https://github.com/NeXt-Warning-System) is a good project to become familiar with. The repos in this Github account contain the work we’ve been prototyping over the last few months. We can cover this together and go through the architecture.
    - There are some hapi boilerplates for building a gov uk front end and api’s using nodejs.
        - [hapi-web-boilerplate](https://github.com/DEFRA/hapi-web-boilerplate)
        - [hapi-api-boilerplate](https://github.com/DEFRA/hapi-api-boilerplate)
    - Here are the dev and test guidelines and standards documents
        - https://github.com/DEFRA/dst-guides
        - https://github.com/DEFRA/software-development-standards
- Hosting & Build environments
    - AWS is usually where code runs for live and test environments. We will probably use Simon’s AWS account in the shot term. This is where we have deployed all XWS work to date. I’ll send you a separate invitation to that account and would be good for you to familiarise with these AWS technologies:
        - SQS
        - SNS
        - Lambda
        - Event Bridge
        - RDS (Postgres)
        - Pinpoint
    - [Jenkins](https://www.jenkins.io/) is used as the build/automation tool. You don’t need to know much about these but you will need access to it and the jobs that are to be set up for this project to do things like start up environment and running build tasks.
