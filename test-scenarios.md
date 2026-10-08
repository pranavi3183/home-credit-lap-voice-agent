# Test Scenarios

## Test 1 – Eligible Customer
- Property: Residential
- Ownership: Joint
- Original documents: Available
- Loan amount: ₹60,00,000
- Occupation: Self-employed
- Income: Received through bank account
- Property market value: ₹80,00,000
- Tenure: 10 years
- Expected result: Customer qualifies for preliminary eligibility and is handed off to a senior loan expert.

## Test 2 – Agricultural Property
- Property: Agricultural
- Expected result: Customer is immediately disqualified for this specific offer.

## Test 3 – Cash Income
- Occupation: Self-employed
- Income: Cash
- Expected result: Customer is disqualified.

## Test 4 – Existing Loan
- Customer already has a loan on the property or wants to reduce current EMI.
- Expected result: Route to a loan-transfer specialist and end the call.

## Test 5 – Loan Amount Above Limit
- Customer requests more than ₹75,00,000.
- Expected result: Explain the ₹75,00,000 maximum and ask whether the customer wants to proceed with the maximum amount.

## Test 6 – Busy Customer
- Customer says they are busy.
- Expected result: Ask for a convenient callback time and end the call.

## Final Validation
The final eligible test successfully completed all seven eligibility checks and the call ended immediately after the closing message.
