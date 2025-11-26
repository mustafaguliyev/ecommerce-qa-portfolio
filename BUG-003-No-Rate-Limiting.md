# BUG-003 – No Rate Limiting on API
**Severity:** High  
**Steps:** Send 12 000 requests in 48 seconds to /api/products  
**Actual:** Server 500 Internal Error (crashed)  
**Expected:** 429 Too Many Requests after 100 req/min
