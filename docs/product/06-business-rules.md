# Nexa Commerce — Business Rules

## Agreed rule: payment at order placement

Customers pay online when placing an order, whether they choose home delivery or store pickup. Payment on delivery and payment at pickup are outside the current scope.

This decision establishes when and where the customer pays. The first-release delivery-charge rule is defined below.

## Agreed rule: first-release payment method

The first release accepts online card payment. Digital wallets and installment payment are not offered in that release. No decision has been made to include those methods later.

## Agreed rule: guest order access

A guest customer provides a mobile number when ordering; email is optional. Nexa gives the customer an order number after the purchase. To access the order later, the guest uses that order number and a verification code sent to the mobile number used for the purchase. This access supports order tracking, eligible cancellation requests, and viewing refund outcomes without requiring an account.

## Agreed rule: first-release customer notifications

Nexa sends essential order updates by SMS to the mobile number used for the purchase. These updates cover order confirmation, the whole pickup order becoming ready, each home-delivery part being handed to the delivery company, a failed delivery attempt because the customer was unavailable, an unexpected shortage affecting the paid order, cancellation of an order or part, and refund outcomes. If a refund to the original card fails, the customer is told that it remains pending and is informed again when the alternative refund succeeds. Updates for a multi-part order identify the affected part so the customer can distinguish it from the rest of the order.

## Agreed rule: refund destination

Refunds for canceled items or accepted returns go back through the original online payment method. Cash refunds at stores and store credit are outside the current scope.

If a refund to the original card payment fails, the refund remains pending and requires customer-support follow-up. Before using an alternative bank account, customer support matches the request to the original order and payment, confirms the identity of the original cardholder, and verifies that the destination bank account belongs to that same person. If any check is incomplete or does not match, the refund remains pending review; Nexa does not send it to another person's account. Once the checks pass, Nexa refunds the amount to the verified account and informs the customer of the outcome. The refund is not treated as completed until the alternative payment succeeds.

## Agreed rule: first-release delivery charge

As a working assumption for the first release, home delivery in Tehran or Karaj has a fixed customer charge of 150,000 toman for the whole order, even if Nexa fulfills it in multiple parts. Store pickup has no delivery charge. The applicable charge is shown before the customer pays. This illustrative amount must be checked against the contracted delivery company's actual terms before launch.

If the entire home-delivery order is canceled before any part is handed to the delivery company, Nexa refunds the delivery charge along with the items. Once a part has been handed over, the delivery charge generally remains when items are canceled or refunded. The agreed exception for parcels lost or damaged while with the delivery company is defined below. The charge also remains when only some items are canceled and the rest will still be delivered. Treatment of delivery charges for later return scenarios remains open.

## Agreed rule: first-release delivery coverage and timing

In the first release, Nexa offers home delivery in Tehran and Karaj only to addresses for which the contracted delivery company has confirmed coverage. Before payment, the customer can see whether home delivery is available for the chosen address and, if it is available, the estimated delivery window. An address outside these cities or outside confirmed carrier coverage is not eligible for home delivery.

As a working assumption for normal home delivery, the estimated window is two to four business days after confirmation of the paid order. The customer sees this estimate before payment. If the order is fulfilled in multiple parts, each part has its own visible estimated window as its fulfillment plan becomes known. These windows are estimates, not guaranteed delivery dates, and must be validated against the carrier's service before launch. Exact address coverage and the business-day calendar also remain to be confirmed.

## Agreed rule: customer price presentation in Iran

Customer-facing amounts are shown in toman. Before payment, the order review shows the applicable tax portion separately and a final payable amount that includes it. Nexa does not assume a single tax rate or exemption for all products; the applicable treatment for its assortment remains to be defined.

## Agreed rule: fixed order prices and partial refunds

The item prices and promotions applied when the customer places and pays for an order remain fixed for that order. Later changes to prices or promotions do not change what the customer agreed to pay.

If an item is canceled or its return is accepted, Nexa refunds the amount actually paid for that item after its share of applicable discounts. The prices and discounts of the remaining items are not recalculated, even if a promotion's original threshold is no longer met. Delivery charges for first-release cancellations follow the rule above; their treatment for later returns remains open.

## Agreed rule: store pickup availability

Store pickup is offered for an item only when that item is already available at the store the customer selects. An item that would need to be transferred from the central warehouse or another location to that store is not eligible for pickup in the current scope.

Stock is set aside for a paid pickup order at the selected store. An unexpected shortage is handled under the stock-shortage rule below.

## Agreed rule: uncollected store pickup

The customer has three calendar days to collect a pickup order after the whole order is ready at the selected store. If the customer does not collect it in that period, Nexa cancels the order, releases the stock set aside for it, and refunds the amount paid under the agreed refund rules.

## Agreed rule: one fulfillment method per order

An order uses either home delivery or pickup at one selected store. A customer cannot combine home delivery and store pickup within the same order in the current scope. Every item in a pickup order must be available at that selected store.

A home-delivery order may be fulfilled in multiple parts supplied from the central warehouse and/or Nexa stores. Those parts may reach the customer separately.

## Agreed rule: home-delivery supply locations

Nexa selects which of its locations supplies each part of a home-delivery order based on available stock. Customers choose home delivery, not the supplying warehouse or store. If an order is supplied in multiple parts, customers can follow the progress of each part separately.

For the first release, Nexa uses stock at the central warehouse for an item when it is available there. For an item unavailable at the warehouse, Nexa chooses an eligible store that has it, giving priority to the store nearest the delivery address. An order can be divided into parts when its items come from different locations.

## Agreed rule: customer unavailable for home delivery

If the customer is unavailable for the first delivery attempt, the contracted delivery company coordinates one further attempt with the customer. If that second attempt also fails because the customer is unavailable, the parcel returns to Nexa. Nexa cancels the affected order part and refunds the amount paid for its items under the agreed refund rule. Other order parts continue independently. The fixed home-delivery charge remains because the parcel was handed to the delivery company.

## Agreed rule: parcel lost or damaged during delivery

If a parcel is lost or damaged while with the contracted delivery company before delivery to the customer, Nexa offers replacement of the affected items from eligible stock without an additional charge. If replacement is unavailable, Nexa refunds the amount paid for those items under the agreed refund rule. Other order parts continue independently. If no part of the order is ultimately delivered because its parcels were lost or damaged and could not be replaced, Nexa also refunds the fixed delivery charge. This exception does not change the charge rule when delivery fails because the customer is unavailable.

## Agreed rule: stock commitment and unexpected shortage

When an order is placed and paid, Nexa sets aside the stock needed for that order. If an item is unexpectedly unavailable during fulfillment, Nexa first looks for another eligible supply location for a home-delivery order. A pickup order remains tied to its selected store; stock from another location is not transferred there for pickup.

If Nexa cannot supply the affected item under the chosen fulfillment method, it cancels that item or order part and refunds the corresponding amount. The remaining fulfillable items continue. The delivery-charge and customer-notification rules above apply.

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
