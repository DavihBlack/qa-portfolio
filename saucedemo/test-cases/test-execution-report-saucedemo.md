# Test Execution Report — SauceDemo E-Commerce Website

**Test Cycle ID:** TCYCLE-01-SAUCEDEMO  
**Date:** 2025-12-06  
**Tester:** Fábio Silva  

---

## Test Summary
This report summarizes the execution of the test cycle for SauceDemo, covering PLP and PDP functionalities, including add to cart, product information consistency and remove from cart functionality.

| Test Case ID | Test Case Title | Status               | Actual Result                  | Bug Link |
|--------------|----------------|--------------------|--------------------------------|----------|
| TC-001       | Product Validation | Fail | PLP shows incorrect image; price mismatch | [Bug Report](../bug-reports/swag-labs-image-price-mismatch.md) |
| TC-002       | Remove Button | Fail | Remove button does not work on some products | [Bug Report](../bug-reports/saucedemo-remove-button.md) |
| TC-003       | Add Product to Cart | Not Executed | *(Pending execution)* | — |

---

## Overall Results

- **Total Test Cases:** 3  
- **Passed:** 0  
- **Failed:** 2  
- **Blocked:** 0  
- **Not Executed:** 1 (TC-003)  

---

## Notes & Recommendations
- Ensure that the product catalog data is consistent between PLP and PDP for all products.  
- Investigate the remove button functionality for items that fail to be removed.  
- Verify add to cart works consistently across different browsers and devices.  
- Update screenshots and screen recordings for documentation if changes occur.  

---

## Attachments
- **Screenshots:** [screenshots](../screenshots/screenshots-saucedemo)
- **Screen Recordings:** [screen-records](../screen-records/)

