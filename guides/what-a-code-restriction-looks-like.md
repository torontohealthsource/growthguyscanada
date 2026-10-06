# Minimums, Exclusions and Why a Code Can Fail on One Cart

Minimums, Exclusions and Why a Code Can Fail on One Cart

- 

 
 

 

# What a code restriction actually looks like in a cart

A code that fails on one cart and works on another is usually hitting a minimum, a product exclusion or a per-account limit — not expiry. Change one variable at a time to tell which.

## The three common restrictions

A minimum purchase, a category or product exclusion, and a single-use or per-account limit. Each produces a different failure: a minimum refuses below a threshold and works above it, an exclusion refuses one product while another works, and a use limit works once and never again.

## How to tell them apart in two minutes

Change one variable at a time. Raise the basket and retry — if it now applies, it was a minimum. Swap the product and retry — if it now applies, it was an exclusion. Try a fresh guest cart with no account — if it now applies, it was tied to the account.

## Why our tests rotate the basket

A code tested against one cart proves only that it works on that cart. Across 662 reads the basket has been rotated over 85 distinct products and from $40.00 to $1,800.00, so a minimum or an exclusion would have surfaced as a failure rather than hiding behind a single repeated test.

## What this does not tell you

That no restriction exists. It tells you none has appeared across the range we have tested. A restriction outside that range would not have been caught, and the honest claim is the narrow one.

HEALTHYLIFE10 takes 10% off sitewide at Growth Guys (growthguys.com), with no minimum
purchase and no product exclusions. Every dated cart test behind that claim is published:
the evidence index, and the
full code page.

## Related

Where a discount code is actually applied, and why the stage matters
- Reading a cart total line by line
- Two reductions do not add, and the difference is real money
- Checking a code yourself, in about two minutes
