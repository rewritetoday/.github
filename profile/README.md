<div align="center">

# Rewrite

**SMS the way it should be** — simple, predictable and absurdly cheap.
Send transactional SMS and OTPs with **flat rate of U$0.01 per message**, no contracts, no surprises and no paperwork.

Made for devs who want **reliability, excellent DX and total control** over SMS sending.

## Integrate in a few lines

</div>

```ts
import { Rewrite } from 'rewritejs'

const client = new Rewrite(process.env.REWRITE_API_KEY)

await client.messages.send({
    from: 'Rewrite',
    to: '+5511999999999',
    content: 'You verification code is 482931',
});
```

<div align="center">

Just like that, the **Rewrite** way of being.

## Don't get stuck with a single provider

**Rewrite** isn't just a gateway — it's an **abstraction layer**.

You can use Rewrite with **multiple SMS providers**, switching or combining depending on price, delivery or region

</div>

- Twilio
- Zenvia
- Direct SMPP
- Other supported providers

<div align="center">

All using **the same API**, the same webhooks and the same **DX**.

Switch providers without rewriting your code.

## Join the SMS revolution

**Rewrite** was born open source because we believe that critical infrastructure **should not be a black box.**

Contribute, discuss ideas, and help build the future of simple, affordable SMS messaging.

**Rewrite** — SMS the way it should be.

</div>
