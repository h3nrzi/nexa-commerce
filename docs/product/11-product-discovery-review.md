# Nexa Commerce — Product Discovery Review

## Review outcome

The product direction, business model, first-release scope, business rules, scenarios, and first-release requirements have been reviewed together. They describe one consumer retailer as the seller, an online purchase journey, and fulfillment through Nexa's central warehouse, stores, and contracted delivery company. The first release covers guest purchase, online card payment, home delivery or store pickup, order tracking, eligible cancellation, delivery exceptions, notifications, and related refunds. Returns, promotions, and optional accounts are planned after the first release.

The agreed product behavior is documented without choosing a technical solution. The first-release requirements remain provisional where the launch inputs below are still missing.

## Launch inputs still needed

| Input | Decision needed before the affected requirement is final |
| --- | --- |
| Product-specific tax treatment | Confirm the applicable treatment for the products Nexa will actually sell in Iran, so the tax portion and final payable amount can be presented accurately. No common rate or exemption has been assumed. |
| Fixed home-delivery charge | The working amount is 150,000 toman per home-delivery order in Tehran or Karaj, regardless of parts. Validate or revise this illustrative amount against the contracted carrier's terms before launch. The rules for when it is retained or refunded are already agreed. |
| Address coverage | Confirm which addresses within Tehran and Karaj the contracted delivery company will serve in the first release. Being in one of those cities alone does not make an address eligible. |
| Delivery windows | The working estimate for normal home delivery is two to four business days from paid-order confirmation. A split order shows a separate estimate for each part as its plan becomes known. Validate or revise the estimate with the carrier and confirm the business-day calendar before launch; it is not a guaranteed date. |

These inputs should be reflected in the [first-release requirements](10-first-release-requirements.md) and checked against the [business rules](06-business-rules.md) before the affected acceptance criteria are treated as final.

## Decisions reserved for later capabilities

- Returns: conditions and time limits for defective or incorrect items, category exceptions, assessment, and treatment of delivery charges.
- Promotions: types, eligibility, and combination rules.
- Payment options beyond online card payment: no later commitment has been made for wallets or installments.

These later decisions do not expand the first-release scope in the [release plan](08-release-scope.md).

## Product discovery completion point

The first-release product definition can be treated as complete when the four launch inputs above are confirmed and the resulting customer-facing amounts, fulfillment choices, and delivery estimates remain consistent across the requirements and scenarios. This review does not authorize or describe architecture, technology choices, or implementation.
