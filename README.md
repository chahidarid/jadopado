# Two-Factor Authentication with Node.js and Authy

NodeJS, Express, BackboneJs

### Local development

1. Install the dependencies.

   ```bash
   $ npm install
   ```

1. Export the environment variables.

   You can find your **Authy Api Key** for Production at https://dashboard.authy.com/. The default MongoDB URL when running MongoDB locally is shown below.

   ```bash
   $ export AUTHY_API_KEY=Your Authy API Key
   $ export MONGO_URL=mongodb://127.0.0.1:27017
   ```

1. Run the server.

   ```bash
   $ node .
   ```

1. Expose your application to the wider internet using [ngrok](http://ngrok.com). You can click
  [here](https://www.twilio.com/blog/2015/09/6-awesome-reasons-to-use-ngrok-when-testing-webhooks.html) for more details. This step
  is important because the application won't work as expected if you run it through localhost.

  ```bash
  $ ngrok http 3000
  ```
  