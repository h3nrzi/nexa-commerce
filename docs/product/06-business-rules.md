# Nexa Commerce — Business Rules

## Agreed rule: payment at order placement

Customers pay online when placing an order, whether they choose home delivery or store pickup. Payment on delivery and payment at pickup are outside the current scope.

This decision establishes when and where the customer pays. The first-release delivery-charge rule is defined below.

## Agreed rule: first-release payment method

The first release accepts online card payment. Digital wallets and installment payment are not offered in that release. No decision has been made to include those methods later.

## Agreed rule: guest order access

A guest customer provides a mobile number when ordering; email is optional. Nexa gives the customer an order number after the purchase. To access the order later, the guest uses that order number and a verification code sent to the mobile number used for the purchase. This access supports order tracking, eligible cancellation requests, and viewing refund outcomes without requiring an account.

## Agreed rule: refund destination

Refunds for canceled items or accepted returns go back through the original online payment method. Cash refunds at stores and store credit are outside the current scope. The exception process if the original payment method cannot receive a refund remains open.

## Agreed rule: first-release delivery charge

Home delivery has one fixed charge for the whole order, even if Nexa fulfills it in multiple parts. Store pickup has no delivery charge. The applicable charge is shown before the customer pays.

If the entire home-delivery order is canceled before any part is handed to the delivery company, Nexa refunds the delivery charge along with the items. If any part has been handed over, the delivery charge remains when other items are canceled or refunded. The charge also remains when only some items are canceled and the rest will still be delivered. The amount of the fixed charge has not been chosen. Treatment of delivery charges for later return scenarios remains open.

## Agreed rule: fixed order prices and partial refunds

The item prices and promotions applied when the customer places and pays for an order remain fixed for that order. Later changes to prices or promotions do not change what the customer agreed to pay.

If an item is canceled or its return is accepted, Nexa refunds the amount actually paid for that item after its share of applicable discounts. The prices and discounts of the remaining items are not recalculated, even if a promotion's original threshold is no longer met. Delivery charges for first-release cancellations follow the rule above; their treatment for later returns remains open.

## Agreed rule: store pickup availability

Store pickup is offered for an item only when that item is already available at the store the customer selects. An item that would need to be transferred from the central warehouse or another location to that store is not eligible for pickup in the current scope.

Stock is set aside for a paid pickup order at the selected store. An unexpected shortage is handled under the stock-shortage rule below.

## Agreed rule: one fulfillment method per order

An order uses either home delivery or pickup at one selected store. A customer cannot combine home delivery and store pickup within the same order in the current scope. Every item in a pickup order must be available at that selected store.

A home-delivery order may be fulfilled in multiple parts supplied from the central warehouse and/or Nexa stores. Those parts may reach the customer separately.

## Agreed rule: home-delivery supply locations

Nexa selects which of its locations supplies each part of a home-delivery order based on available stock. Customers choose home delivery, not the supplying warehouse or store. If an order is supplied in multiple parts, customers can follow the progress of each part separately.

For the first release, Nexa uses stock at the central warehouse for an item when it is available there. For an item unavailable at the warehouse, Nexa chooses an eligible store that has it, giving priority to the store nearest the delivery address. An order can be divided into parts when its items come from different locations.

## Agreed rule: stock commitment and unexpected shortage

When an order is placed and paid, Nexa sets aside the stock needed for that order. If an item is unexpectedly unavailable during fulfillment, Nexa first looks for another eligible supply location for a home-delivery order. A pickup order remains tied to its selected store; stock from another location is not transferred there for pickup.

If Nexa cannot supply the affected item under the chosen fulfillment method, it cancels that item or order part and refunds the corresponding amount. The remaining fulfillable items continue. The delivery-charge rule above applies; the customer notification policy remains open.

## Agreed rule: customer-requested cancellation

A customer can cancel a whole order while all its parts remain eligible, or cancel only the eligible items or parts of an order. For home delivery, an item or part remains eligible until it is handed to the contracted delivery company. For store pickup, it remains eligible until the customer collects it at the store.

After those points, cancellation is no longer available for the affected item or part. A customer who has received it can instead request a return under the return policy. Nexa refunds the amount due for canceled items or parts under the fixed-price rule above.

## Agreed rule: return channels

After receiving an eligible item, a customer may return it at any Nexa store or through the contracted delivery company. The choice of return channel does not depend on whether the original order was delivered to the home or collected from a store.

Return eligibility and refund approval follow the policy below. Product-category exceptions remain open.

## Agreed rule: reasons for return

A customer may request a return for an item that is defective, an item that differs from what was ordered, or a change of mind. For a change of mind, the customer must request the return within 30 days of receiving that individual item, whether by home delivery or store pickup. The item must be in good condition and complete. For a multi-part order, each item's 30-day period starts when that item is received.

The conditions and time limits for defective or incorrect items will be defined separately. Product-category exceptions, the detailed inspection process, and the refund decision process also remain open.

## Rules to define next

- The policy for defective or incorrect items, product-category exceptions, and inspection criteria
- Promotion eligibility and combination rules, plus treatment of delivery charges for later returns
