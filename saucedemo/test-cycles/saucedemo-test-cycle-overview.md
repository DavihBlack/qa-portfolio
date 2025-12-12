# Test Cycle Overview — SauceDemo E-Commerce Website

**Cycle ID:** TCYCLE-01-SAUCEDEMO
**Test Cycle Name:** Sauce Demo PDP, PLP & Cart Functionality
**Date:** 2025-12-04  
**Tester:** Fábio Silva  

---

## Objective
The objective of this test cycle is to validate core functionalities of the SauceDemo e-commerce website, ensuring that the product listing page (PLP) and product detail page (PDP) display accurate information, the add/remove cart functions work correctly and the overall user experience meets quality standards.

---

## Scope
- Functional testing of PLP and PDP
- Add to cart and remove from cart functionality
- Product image and price consistency between PLP and PDP
- Basic UI/UX verification

---

## Out of Scope
- Payment gateway
- Checkout process
- Performance and load testing
- Everything that's not related to what's in scope

---

## Test Environment
- **Browser:** Safari 26.1 
- **OS:** macOS Tahoe 26.1 
- **Network:** Wi-Fi, stable connection

---

## Test Data
- Registered user account with valid credentials
- Pre-existing products in the catalog

---

## Risks & Assumptions
- Assumes stable network and website availability
- Assumes valid test data is preloaded
- Known limitation: Demo site may reset periodically

---

## Entry Criteria
- Test environment is configured
- Test accounts created
- Test data validated

---

## Exit Criteria
- One test case left to be executed
- All critical and major bugs logged
- No open blockers

---

## Test Cases Included
| Test Case ID | Title |
|--------------|-------|
| TC01         | Verify product images and prices consistency (PLP vs PDP) | 
| TC02         | Verify “Remove” button functionality on PLP and PDP |
| TC03         | Verify “Add to Cart” functionality from PLP and PDP |

---

## Deliverables
- Test Cycle Overview (this document)
- Individual Test Case documents
- Execution Report with status and linked bug reports