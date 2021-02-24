---
title: About
---

# Integrate Stripe Customer Portal

!!! info ""
    The **Stripe Customer Portal** enables users to self-serve subscriptions for an application
    _so we don't have to_.

## Why should we care?

The portal handles:

* **Subscriptions**
* **Billing**
* **Invoices**
* **Payments**

Which is a lot.

## How does it work?

The basic flow is:

!!! green ""
    1. We tell Stripe about our products.
    2. We send users to the portal.
    3. The portal tells us when users buy our products.

We can do the first of these manually. For the others we need a server.

