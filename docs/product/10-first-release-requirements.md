# Nexa Commerce — First Release Product Requirements

## Goal and status

The first release lets a customer buy online as a guest, receive an order through home delivery or store pickup, follow its progress, and cancel eligible items with a refund. Nexa can operate that journey across its central warehouse, stores, and contracted delivery company.

These requirements translate the agreed product scope into observable outcomes. The remaining product decisions at the end must be settled before the affected acceptance criteria are final. This document describes product behavior, not how it is built.

## Customer purchase

### R1 — Product offer

Customers can find Nexa's offered products and see the information needed to choose an item, including its brand, current price, and availability. Nexa is identified as the seller, including for products made by other brands.

**Acceptance criteria**

- An item unavailable for the chosen fulfillment method cannot be placed in an order using that method.
- A product's brand does not appear as an independent seller.

### R2 — Fulfillment choice

Customers choose either home delivery or pickup at one store for the entire order. Nexa shows only eligible choices for the selected items.

**Acceptance criteria**

- Pickup at a store is offered only when every item in the order is already available at that store.
- The customer cannot combine delivery and pickup in one order or request a transfer to make pickup available.
- For home delivery, Nexa chooses supply locations; the customer does not select them.

### R3 — Order review and price

Before paying, the customer can review the selected items, fulfillment choice, item prices, any applicable delivery charge, and the amount to be paid. The accepted item prices remain fixed for the paid order. Promotions are not part of the first release.

**Acceptance criteria**

- The amount shown for payment reflects the items and charges in the order review.
- Store pickup has no delivery charge; home delivery has one fixed charge for the order even if it is fulfilled in parts.
- A later change to a product price does not change an already paid order.

### R4 — Guest order and online payment

A customer can place an order without creating an account, provides a mobile number, and pays online by card when placing it. Email is optional. Payment at delivery or pickup is not offered.

**Acceptance criteria**

- A guest cannot complete the purchase without a mobile number; providing an email address is optional.
- A guest can complete the purchase and receive an order confirmation after successful payment.
- The confirmation includes an order number. A guest can later access that order with the order number and a verification code sent to the mobile number used for purchase.
- An unsuccessful or incomplete payment does not produce a confirmed paid order.
- Digital wallets and installment payment are not offered in the first release.
- Guest order access supports progress tracking, eligible cancellation requests, and refund outcomes without account creation.

## Order fulfillment

### R5 — Stock commitment and shortage

Nexa sets aside the needed stock when an order is placed and paid. If stock is unexpectedly unavailable later, Nexa first seeks another eligible location for a home-delivery item. A pickup order stays with its chosen store.

**Acceptance criteria**

- A shortage at one home-delivery location can be resolved from another eligible Nexa location.
- If an item cannot be supplied under the chosen method, only that item or part is canceled and refunded; fulfillable items continue.
- Nexa does not transfer stock to another store to save a pickup order.

### R6 — Home delivery in parts

Nexa can fulfill a home-delivery order in separate parts from the central warehouse and/or stores and hand the parts to the contracted delivery company.

**Acceptance criteria**

- Stock at the central warehouse supplies an item first; if it is unavailable there, an eligible store with stock nearest the delivery address supplies it.
- The customer can see the progress of each part separately, including when parts are delivered at different times.
- A part may progress independently without changing the agreed prices of other parts.

### R7 — Store pickup

The selected store prepares a paid pickup order using items available at that store and hands it to the customer.

**Acceptance criteria**

- The customer can tell when the order is ready for collection and when it has been collected.
- No payment is requested at the store for the order.

## Cancellation and refund

### R8 — Customer cancellation

A customer can cancel the whole order while all parts remain eligible, or only eligible items or parts. For home delivery, eligibility ends when the affected part is handed to the delivery company. For pickup, it ends when the customer collects it.

**Acceptance criteria**

- An eligible part can be canceled while another part continues.
- A handed-over delivery part or collected pickup item cannot be canceled through this path.
- The remaining items keep their original prices.

### R9 — Refund for cancellation or shortage

Nexa refunds the amount paid for each canceled item. The refund goes through the original online payment method.

**Acceptance criteria**

- The refund concerns only canceled items or parts; other fulfillable items continue.
- If the whole home-delivery order is canceled before any part is handed to the delivery company, the delivery charge is refunded.
- If a part has been handed over, or the remaining items will still be delivered, the delivery charge remains.
- If a refund to the original card fails, the refund remains pending for customer-support follow-up. After the original cardholder is verified, the amount is sent to a verified bank account in that person's name, and the customer is informed of the outcome.
- Cash refund at a store and store credit are not offered.
- The customer can learn the outcome of the refund.

## Retail operations

### R10 — Operate the journey

Nexa's commercial team can maintain the assortment and prices. Inventory, warehouse, and store staff can keep availability current and progress their assigned order parts. Customer support can see the customer's order and help resolve cancellation, shortage, and refund issues. The delivery company carries home-delivery parcels and provides delivery outcomes.

**Acceptance criteria**

- Nexa can distinguish availability at the central warehouse from availability at each store when offering delivery or pickup.
- Nexa can distinguish parts awaiting preparation, handed to the delivery company, ready for pickup, and completed, so the agreed cancellation cutoffs can be applied.
- Customer support can identify which items were fulfilled, canceled, or refunded when helping a guest customer.

## Outside the first release

Customer accounts, returns after delivery or collection, and promotions are planned later. Marketplace sellers, B2B commerce, in-store checkout, mixed delivery-and-pickup orders, payment at handover, loyalty programs, gift cards, cash refunds, and store credit remain outside the current product scope.

Digital wallets and installment payment are also absent from the first release; no later commitment has been made for them.

## Remaining first-release product decisions

- Choose the monetary unit shown to customers in Iran and define how any applicable tax is reflected in the price they see.
- Set the fixed home-delivery charge amount, delivery coverage, and timing promises.
- Set the period for collecting a pickup order and what happens if it is not collected.
- Define what happens after a failed home-delivery attempt or an undeliverable parcel.
- Define when customers are notified about shortages, cancellations, and refund outcomes, including failure of a refund to the original card.
- Define the business checks customer support uses to confirm the original cardholder before an alternative bank-account refund.
