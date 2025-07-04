# Facebook Webhook Example

This is a basic Node.js server that:
- Verifies webhook with Facebook App
- Receives Messenger messages
- Sends auto reply

## Setup
1. Create a Facebook App
2. Enable Messenger
3. Set webhook URL to: https://yourdomain.com/webhook
4. Use VERIFY_TOKEN as set in .env
5. Add PAGE_ACCESS_TOKEN from Facebook Graph API

Run server:
> npm install
> node index.js
