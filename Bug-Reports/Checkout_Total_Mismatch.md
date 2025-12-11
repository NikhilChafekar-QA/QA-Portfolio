Bug Report – Checkout Total Price Mismatch

Bug ID: BUG_CHECKOUT_07
Module: Checkout
Severity: Critical
Priority: High
Reported By: Nikhil Chafekar
Environment: Chrome 120, Windows 10

Summary

The total amount displayed in the cart does not match the total shown during checkout.

Steps to Reproduce

Add two products to the cart

Proceed to the Checkout page

Compare the Cart Total with the Checkout Total

Expected Result

The total amount should remain consistent between the Cart and Checkout pages with no unexplained differences.

Actual Result

The Checkout page shows an extra ₹50 added to the total without any explanation or label.

Additional Notes

Likely related to incorrect or missing tax/fee calculation logic.

Could be an unlabelled shipping fee, GST rounding issue, or a UI calculation bug.
