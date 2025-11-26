# BUG-001 – Zero-Price Checkout Bypass
**Severity:** Critical  
**Priority:** High  
**Environment:** Staging  
**Steps to Reproduce:**
1. Add any product to cart
2. Set quantity to 0
3. Click “Proceed to checkout”
4. Complete payment  
**Actual Result:** Order created with total 0.00 AZN  
**Expected Result:** Validation error “Your cart is empty”  
**Impact:** Direct revenue loss  
**Status:** Reported → Fixed in v2.3.1
