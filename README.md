# Commentwo

## What + why

This repo is a fork of [Commento++](https://github.com/souramoo/commentoplusplus) which itself was a fork of [Commento](https://gitlab.com/commento/commento). Both projects appear to not be maintained anymore so I decided to create my own fork which I will use to add commenting functionality to [Reloco](https://reloco.xyz/).

## Deploy

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/Ys0K44?referralCode=faraz)

The button above allows you to do a one-click deploy to Railway. The pre-populated variables set up the basic configuration to have a working Commentwo instance.

## Configuration

The basic configuration does not include the email setup. To get emails working on your Commento instance, configure the following variables:
- COMMENTO_SMTP_FROM_ADDRESS
- COMMENTO_SMTP_HOST
- COMMENTO_SMTP_USERNAME
- COMMENTO_SMTP_PASSWORD
- COMMENTO_SMTP_PORT

## Frontend

Once your Commento instance is live, you can integrate it into your client by adding a `script` + a `div` tag.
```html
<script defer src="https://{{YOUR_COMMENTO_SERVER_DOMAIN}}/js/commento.js"></script>

<div id="commento"></div>
```

## Notes
- [Original docs](https://docs.commento.io/): The docs site for the original project. I am not sure how long it'll be around though.
