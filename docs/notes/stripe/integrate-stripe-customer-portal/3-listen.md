---
title: Step 3 - Listen to webhooks
---

# Step 3 - Listen to webhooks

By now we have a **session** between our **app** and the **portal**.

This session is **long-lived**. Whenever the user makes a change to their
subscription then the portal will try to tell us.

!!! info ""
    The **portal** is talking so we need a way of **listening**.

## Webhooks

A **webhook** is simply a route on our server that we have created to receive data 
from a source we are interested in.

> Webhooks are designed to avoid polling (i.e. instead of us repeatedly asking if something 
has changed, we just wait to be told).

TBD ...
