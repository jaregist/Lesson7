# READ ME

## How To Use
1. pull/download code to local computer
2. run 'yarn' in command line to install dependencies
3. run 'yarn development'
4. open http://localhost:3000/ once server starts

## Current Issues
1. Connecting with Stripe seems to be throwing an issue -- I thought the Strip Auth code may be missing from the config.js file. After adding, it did not seem to fix. Will keep digging around for an answer.
2. Checkout/Cart page don't seem to be working properly. I think this is tied in with the Stripe issue as I have no authorized Strip Seller instances so, it should not load a checkout page as there is no way to actually checkout