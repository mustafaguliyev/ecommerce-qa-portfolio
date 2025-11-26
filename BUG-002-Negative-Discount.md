# BUG-002 – Empty Coupon Applies Negative Discount
**Severity:** Critical  
**Steps:**
1. Go to cart
2. Leave coupon field completely empty
3. Click “Apply Coupon”  
**Actual:** Total became -150 AZN (system should pay user)  
**Expected:** Nothing happens or “Enter coupon” error
