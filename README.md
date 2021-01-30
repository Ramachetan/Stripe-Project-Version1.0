# stripe-subscriptions-sca

This repository shows you how to use Node (version 8+) and Stripe to create recurring subscriptions with built-in SCA support. It is an updated version of [stripe-recurring-subscriptions](https://github.com/code-nebula/stripe-recurring-subscriptions).

It uses Express for creating a simple server, Nunjucks for templating, and the Stripe API.

## Instructions

1. Clone this repository
2. Run `npm install` to install all dependencies
3. Create a `.env` file to house your Stripe Secret Key (this repo includes `.env` in its `.gitignore`)
4. In the `.env` file, set your secret key as STRIPE_API_KEY (`STRIPE_API_KEY="sk_test_************************"`)
5. In the Javascript section of the `views/register.html` file, replace `var stripe = Stripe("pk_test_************************")` with your Stripe Publishable Key
6. Run the app via `npm run start`
7. Navigate to [localhost:3000](http://localhost:3000/)


