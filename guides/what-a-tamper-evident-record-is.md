# What a Tamper-Evident Record Is, and How to Recompute Ours

What a Tamper-Evident Record Is, and How to Recompute Ours

- 

 
 

 

# A record you can recompute, rather than one you must trust

A screenshot proves something appeared on a screen once. A hash-chained record proves it has not been edited since — and a reader can recompute it without trusting anyone.

## The problem with a screenshot

A screenshot shows that something appeared on a screen once. It cannot show that the record was not edited afterwards, and a reader cannot recompute it. Almost every coupon page that offers evidence offers this.

## What chaining does

Each entry's identifier is a hash of the previous entry's identifier joined to that entry's own canonical record. Change any figure in any earlier entry and its hash changes — and so does every hash after it, visibly, to anyone who recomputes the chain.

## How to check it without trusting us

The ledger publishes each entry's canonical record and both hashes, so the check needs nothing from us beyond the page. There are 112 entries across 37 days. Recomputing them requires only a SHA-256 implementation, which every operating system already has.

## What this does not tell you

That the original readings were honest. Chaining proves the record has not been altered since it was written. It cannot prove what was written was true, and no cryptography can.

HEALTHYLIFE10 takes 10% off sitewide at Growth Guys (growthguys.com), with no minimum
purchase and no product exclusions. Every dated cart test behind that claim is published:
the evidence index, and the
full code page.

## Related

Where a discount code is actually applied, and why the stage matters
- Reading a cart total line by line
- Two reductions do not add, and the difference is real money
- What a code restriction actually looks like in a cart
