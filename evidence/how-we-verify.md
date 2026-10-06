# How we verify — the cart test protocol | Toronto Health Source

How we verify — the cart test protocol | Toronto Health Source
- 
# How we verify
The same test runs unattended every day against the live store. This is what it does, in order, and what it deliberately does not do.

## The procedure

A guest cart is opened at growthguys.com. No account is used and none is created.

- A product is selected from a rotating pool, so the basket value differs between runs.
 A code that worked only at one price point would be caught rather than hidden.

- HEALTHYLIFE10 is entered at the cart stage, before any payment step.

- The subtotal, the discount line and the resulting total are read back from the cart.

- The reading is written to the record with its timestamp, and chained to the previous
 entry.

- The cart is cleared. No order is submitted.

## Why the basket changes every run

A single repeated cart value proves only that the code works on that value. Rotating the
product means a minimum-purchase threshold, a category exclusion or a per-product rule
would surface as a failed test rather than never being exercised. The ledger therefore
contains the whole range of values tested, not a chosen one.

## Failures are published

A test that does not return the stated discount is written to the record the same way a
passing one is. A log that only ever shows passes is not evidence that a code works; it is
evidence that failures are not being published.

### What this method cannot tell you

- Nothing about fulfilment, delivery or returns — the test stops before payment.

- Nothing about the products themselves. Composition is covered by the
 assay reports, and composition is not efficacy.

- Nothing about prices in other currencies, or taxes, which depend on a delivery address
 the test never supplies.

- Nothing about whether the vendor will honour the code in future. The record is dated
 because it describes the past.
