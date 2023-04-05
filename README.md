# Twilio

## Prerequisite

1. Install the Twilio CLI
```bash
npm install -g twilio-cli
```
2. Obtain your Account SID and Auth Token:
- Log in to your Twilio account at https://www.twilio.com/login.
- Go to the Twilio Console: https://www.twilio.com/console/tokens
- On the Console Dashboard, you will find your Account SID and Auth Token. Note them down or keep the browser tab open as you will need them in the next step.

3. Configure the Twilio CLI with your Account SID and Auth Token:
In your terminal or command prompt, run the following command:
```bash
twilio login
```

To summarize, when you use twilio login and provide your Account SID and Auth Token:
1. The Twilio CLI creates a new API Key and Secret associated with your Twilio account.
2. The CLI then stores the API Key and Secret in a profile on your local machine for future use.
3. The primary Auth Token is discarded and not stored locally.

Once you have logged in using the twilio login command, the Twilio CLI will use the API Key and Secret for authentication in subsequent commands. This ensures a secure way to interact with your Twilio account without storing the primary Auth Token on your local machine.

## Flex

### Setup

- [ ] Sign up for a Twilio account: If you haven't already, you'll need to sign up for a Twilio account at https://www.twilio.com/try-twilio. Once you have signed up, you will be provided with your account SID and auth token, which you will need later in the setup process.

- [ ] Install Node.js and npm: Twilio Flex is built on top of Node.js and requires it to run. You can download and install Node.js from the official website: https://nodejs.org/en/. npm is the package manager for Node.js and comes bundled with the Node.js installation.

- [ ] Install the Twilio CLI: The Twilio CLI is a command-line tool that helps you manage your Twilio resources. You can download and install the CLI from the official website: https://www.twilio.com/docs/twilio-cli/quickstart.

- [ ] Install the Flex Plugin Builder: The Flex Plugin Builder is a command-line tool that helps you build and package Flex plugins. You can install it by running the following command in your terminal: `npm install -g @twilio/flex-plugin-builder`

1. Create new Flex project or clone existing by using the following commands:

```shell
/New
twilio flex:init

/Existing
twilio flex:clone <project-name>
```
