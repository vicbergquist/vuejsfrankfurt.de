# Netlify lambdas

## What you can see here

This adds some Netlify lambda functions to the project. 

They will be triggered automatically once a new deploy starts, fails or succeeds.
They currently send out notifications using Telegram.

In order to test it locally you'll need to setup a `.env.local` file with the corresponding API token and chat ID.

To make it work on Netlify you'll neet to setup the values as environment variables. 

## Resources

Netlify Lambda Functions: https://www.netlify.com/docs/functions/

Telegram Bots API: https://core.telegram.org/bots/api

