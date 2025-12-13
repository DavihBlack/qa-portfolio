# Test Cycle Overview — Buggy Cars Rating Website

**Test Cycle ID:** TCYCLE-01-BUGGYCARS  
**Test Cycle Name:** Buggy Cars Navigation & Page Loading  
**Date:** 2025-12-04  
**Tester:** Fábio Silva  

---

## Objective
Verify that the Buggy Cars Rating website functions correctly, focusing on navigation, car model page loading, and general user interaction with the product listings.

---

## Scope
- Navigation from homepage to car brand pages  
- Navigation from car brand pages to specific car model pages  
- Page loading and response for all car models  

**Out of Scope:**  
- Functional testing of features not related to navigation (e.g., ratings submission, comments, or user registration)  
- Everything that's not related to what's in scope

---

## Test Environment
- **Website URL:** https://buggy.justtestit.org/  
- **Browser:** Safari 26.1  
- **Operating System:** macOS Tahoe 26.1  
- **Network:** Wi-Fi, stable connection 

---

## Risks & Assumptions
- Assumes stable network and website availability  
- Assumes valid test data is preloaded  
- Known limitation: Demo site may have intermittent loading issues  

---

## Entry Criteria
- Test environment is configured  
- Test accounts created  
- Test data validated  

---

## Exit Criteria
- All planned test cases executed  
- All critical and major bugs logged  
- No open blockers  

---

## Test Cases Included
| Test Case ID | Title |
|--------------|-------|
| TC-001       | [Verify that clicking on car models from any section navigates to the correct car model page](buggy-cars/test-cases/tc-01-buggy-cars-navigation.md) | 
| TC-002       | [Verify that clicking on Popular Make section navigates to the correct section](buggy-cars/test-cases/tc-002-popular-make.md) | 
| TC-003       | [Verify that clicking on Overall Rating section navigates to the correct section](buggy-cars/test-cases/tc-003-overall-rating.md)|
 
---

## Test Data
- Registered user account with valid credentials
- Pre-existing car models in the catalog  

---

## Test Deliverables 
- Test Cycle Overview (this document)
- Individual Test Case documents
- Execution Report with status and linked bug reports

---

## Notes
- The website may contain occasional delays or unresponsive pages - testers should note these occurrences.  
- Additional test cases may be added in future cycles as new features are implemented.

[def]: buggy-cars/test-cases/tc-003-overall-rating.md