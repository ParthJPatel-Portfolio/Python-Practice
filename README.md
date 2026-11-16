# Repository for Python Practice

# Python Practice: Numerical Operators & Conditional Statements
## Overview
This exercise demonstrates fundamental Python programming concepts through a simulated movie ticket-booking system. The program evaluates booking eligibility, determines applicable discounts and additional charges, assigns service fees based on seat selection, and calculates the final ticket price.

## Concepts Practiced

- **Variables and Data Types:** Working with integers, strings, and Boolean values.
- **Arithmetic Operators:** Using `+` and `-` to calculate the final ticket price.
- **Comparison Operators:** Using `>`, `>=`, and `!=` to evaluate conditions.
- **Conditional Statements:** Applying `if`, `elif`, and `else` to control program execution.
- **Logical Operators:**
  - `and` – Checks whether multiple conditions are satisfied.
  - `or` – Checks whether at least one condition is satisfied.
- **Nested Conditions:** Using conditional statements inside other conditional blocks.
- **Formatted Strings (f-strings):** Displaying calculated values dynamically.

## Scenario: Movie Ticket Booking

The program simulates a ticket-booking process using the following sample information:

| Variable | Value |
|---|---|
| Base Price | $15 |
| Age | 21 |
| Seat Type | Gold |
| Show Time | Evening |
| Membership | False |
| Weekend | False |

## Program Logic

The program follows several steps to determine the booking outcome:

1. **Ticket Eligibility:** Checks whether the user is older than 17.
2. **Evening Show Eligibility:** Determines whether the user meets the minimum age requirement of 21.
3. **Membership Discount:** Applies a $3 discount if the user is a member and at least 21 years old.
4. **Additional Charges:** Adds $2 for evening shows or weekend bookings.
5. **Booking Validation:** Combines multiple conditions using logical operators to determine whether the booking requirements are satisfied.
6. **Service Charges:** Assigns fees according to the selected seat type:
   - Premium: $5
   - Gold: $3
   - Standard/Other: $1
7. **Final Price Calculation:** Calculates the ticket cost by combining the base price, additional charges, service fees, and applicable discounts.

## Final Price Calculation

The program uses the following formula:

```python
final_price = base_price + extra_charges + service_charges - discount
```

With the sample values:

| Component | Amount |
|---|---:|
| Base Price | $15 |
| Extra Charges | +$2 |
| Gold Seat Service Charge | +$3 |
| Membership Discount | -$0 |
| **Final Ticket Price** | **$20** |

## Expected Output

```text
User is eligible to book a ticket
User is eligible for Evening shows
User does not qualify for membership discount
Discount: 0
Extra charges will be applied
Extra charges: 2
Ticket booking condition satisfied
Service charges: 3
Final price of ticket: 20
```

## Key Takeaways

This exercise reinforced the fundamentals of Python decision-making and numerical calculations. It provided hands-on practice combining conditional statements, Boolean logic, comparison operators, and arithmetic operations to simulate a real-world ticket-booking scenario.

## Technologies
- Python 3
