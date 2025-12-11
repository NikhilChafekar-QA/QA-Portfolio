Checkout Module – Test Scenarios

Below are the high-level test scenarios to validate the end-to-end Checkout functionality.

Test Scenarios List
1. Verify checkout process with valid address and payment
User enters a valid shipping address.
User selects a valid payment method.
Checkout should complete successfully.

2. Verify checkout with invalid or blank address
User keeps required address fields blank or enters invalid details.
System should display appropriate validation errors and block checkout.

3. Verify applying a coupon code
User enters a valid coupon code.
Discount should apply correctly to the order total.
System should show a confirmation message (e.g., “Coupon applied successfully”).

4. Verify removing an item during checkout
User removes an item from the checkout item list.
Total amount should update instantly and accurately.

5. Verify price consistency between cart and checkout
Amount shown in the Cart should match the Checkout total (excluding clearly displayed shipping/taxes).
No unexpected or hidden charges should appear.

6. Verify shipping charges are applied correctly
Shipping fee should be calculated based on rules (location, weight, free-shipping eligibility, etc.).
Charge should be displayed clearly before final payment.

7. Verify user is redirected to order confirmation page after successful payment
After payment success, user should automatically be redirected to the Order Confirmation page.
Order ID and summary should be visible.
