---
title: "Send SMS With Twillio"
points: 13
difficulty: complex
tags:
  - backend
  - sms
  - twillio
dependencies:
unlocks:
---

## Description:

Utilize [Twillio](https://www.twilio.com/en-us) to send SMS messages to customers when an order is created.

_Note: we don't currently take phone number as a part of the create order request body, so feel free to hard the desired phone number_

Add a new `sms` folder within the `service/src/infrastructure` folder that contains any code you write relating to sending phone messages.

## Acceptance Criteria:

When an order is created, a text should be sent to the desired phone.
