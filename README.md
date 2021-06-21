# ORDERS-EXERCISE

Hello there! If you're here, chances are somebody at Mozantech thinks you're talented. 
This exercise is part of our recruitment process. 
It is designed to help us understand some of your competencies before moving forward.

## Goal

We have a few requirements for you to follow but we want you to build this with your own style and ideas.

The main goal of the exercise is to build a REST API to support our store shipment process.
We have simple products but sometimes the clients orders are too complex to track on paper... 

Our products have: 
- id
- name
- price

This gets complex with the wide variaty of payment methods that we support:
- Credit card
- Multibanco
- Paypal

Some of them have different flows and may impact the order price.
For example, if you use Paypal you get a humble 10% off. Or if you use Multibanco we need to send an email to the client with the reference.

(Please note that you should mock the email implementation by just logging "email sent" to the console)

On top of this, we are adding new payment methods every month to the platform. 

**PS**: The payment process will have a direct impact on the order status.

We only need 2 endpoints:
- List orders
- Order

What you'll need:
- A way to persist your data (keep it simple)
- A public repo to share your work with us
- An accurate README to show us how to run your app
- You should not use this repo

What we value: 
- Tests
- Your unique skills


