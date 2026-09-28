# Nexa Commerce — Product Direction

## Decision

Nexa Commerce is an **enterprise omnichannel retail commerce platform for a single large retailer**. The retailer sells products from multiple brands, operates multiple stores and fulfillment locations, and is the seller to the customer. A third-party brand may supply products, but it is not a seller on the platform.

The product supports a connected shopping and order experience across the retailer's channels and locations. Its scope allows for home delivery and store pickup, including orders fulfilled in multiple parts when items come from different locations or are ready at different times.

## Commerce scope

Nexa Commerce covers the retail commerce lifecycle at a product level:

- Product offerings, pricing, and promotions
- Inventory availability across the retailer's locations
- Order placement and management
- Customer payments
- Fulfillment, including delivery and pickup
- Cancellation, returns, and refunds

These are scope boundaries, not a commitment to specific features or operational rules. The details of each area will be defined in later product work.

## Why this model

| Model | Product fit |
| --- | --- |
| D2C or simple store | Easier to define, but too narrow to represent the operational breadth of a large retailer. |
| Large retailer | Adds meaningful scale, assortment, pricing, inventory, and order complexity under one business. |
| Omnichannel retailer | Adds coordination between online shopping, stores, delivery, pickup, and fulfillment locations; this is the intended enterprise retail challenge. |
| Marketplace | Adds independent sellers and a separate commercial relationship with each seller, expanding the scope beyond retail operations. |
| B2B commerce | Centers on organizational purchasing and procurement needs rather than the consumer retail journey chosen for Nexa. |

**Single-Retailer Omnichannel Retail** provides substantial enterprise product complexity while keeping ownership of sales and operations within one retailer. It is the chosen balance between a realistic, broad commerce lifecycle and a controllable scope.

## Out of scope for now

- Third-party marketplace participation or independent sellers
- Seller onboarding
- Seller commissions and payouts
- Seller disputes
- B2B procurement and commerce
- Customer loyalty programs
- Gift cards
