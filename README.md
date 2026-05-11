README_Plastics_Bug_Report.md
# Plastics Inc. – Manual Testing Bug Report

## Project Overview

This repository contains the manual testing bug report and QA findings for the **Plastics Inc. B2B web application**. The testing focused on identifying functional bugs, UI/UX inconsistencies, validation issues, workflow problems, access-control concerns, and cart/order-related defects across key user flows.

The bug report is documented in an Excel file and can be used by the development team to review, prioritize, reproduce, and resolve reported issues.

---

## Repository Contents

```bash
Plastic Bug Reports.xlsx
README.md
```

---

## Testing Summary

| Item | Details |
|---|---|
| Project Name | Plastics Inc. B2B |
| Testing Type | Manual Functional Testing |
| Platform | Web Application |
| Total Reported Issues | 96 |
| Test Documentation | Excel Bug Report |
| Evidence Type | Screenshot / Video Links |
| Primary Focus | Functional, UI/UX, Validation, Cart, Order, Account, and Workflow Testing |

---

## Priority Summary

| Priority | Total Issues |
|---|---:|
| High | 21 |
| Medium | 48 |
| Low | 26 |
| Unspecified | 1 |

---

## Modules / Areas Covered

- **Product Page:** 12 issues
- **Order History:** 10 issues
- **Brand Page:** 10 issues
- **Checkout Page:** 9 issues
- **Home Page:** 8 issues
- **Product Details Page:** 8 issues
- **Registration Page:** 5 issues
- **Cart Page:** 5 issues
- **Login Page:** 4 issues
- **Home Page Search Bar:** 4 issues
- **Our Vendors:** 4 issues
- **Request For Login Page:** 3 issues
- **Header Menu:** 3 issues
- **Product History Page:** 2 issues
- **My Profile:** 2 issues
- **Search With result:** 2 issues
- **Home Page Mobile View:** 1 issue
- **About Us:** 1 issue
- **Our Team:** 1 issue
- **Improvement:** 1 issue

---

## Testing Scope

The testing covered the following major areas:

- Login and authentication flows
- Forgot password and OTP verification
- Registration and request-access workflows
- Product listing and filtering
- Product details page behavior
- Cart and checkout workflows
- Order history and order review flows
- Product history
- Favorites / personal list behavior
- Address and contact management
- Homepage, header, navigation, and search behavior
- Brand and vendor pages
- Mobile and responsive layout checks
- UI spacing, visibility, alignment, and button styling

---

## Key Issues Identified

Some major issue categories found during testing include:

- Cart state not updating properly without page refresh
- Product added to cart count showing but cart page showing empty
- Order history filters not returning expected data
- Date filter causing order history data to disappear
- Personal favorite lists visible from another account
- Server-side errors during address creation and order actions
- OTP not received during forgot password flow
- Form validation accepting invalid email or phone inputs
- UI spacing issues between header, content, and footer
- Low-contrast or unclear labels
- Button styling and alignment inconsistencies
- Product/vendor names overflowing outside their containers
- Quantity control buttons too close to input fields
- Add-to-cart button label/state inconsistencies

---

## Bug Report Format

The Excel bug report includes the following columns:

| Column | Description |
|---|---|
| #SL | Serial number |
| Module | Application module |
| Type Of Testing | Testing category |
| Feature | Feature or page where the issue was found |
| Test Cases | Test scenario or bug title |
| Expected Result | Expected system behavior |
| Actual Result | Observed system behavior |
| Reproducing Steps | Steps to reproduce the issue |
| Screen Shot | Screenshot or video evidence |
| Priority | Bug priority |
| Status | Current status or comment |

---

## Testing Types Performed

### Functional Testing
Validated whether key features worked according to expected behavior.

### UI/UX Testing
Checked layout, alignment, spacing, visibility, readability, and button/component consistency.

### Validation Testing
Verified field-level validation for email, phone number, required fields, dropdowns, and form submission behavior.

### Workflow Testing
Tested full user journeys such as login, product selection, add to cart, checkout, order review, and order history.

### Regression-Focused Testing
Checked whether previously working flows remained stable after navigation, filtering, refresh, or state changes.

---

## Recommended Improvements

- Fix cart and order state synchronization issues.
- Improve API/server-side error handling and validation.
- Ensure order history filters return accurate and persistent results.
- Enforce proper access control for personal favorite lists.
- Standardize button design, spacing, and interaction states.
- Improve form validation for email, phone, and required fields.
- Add proper loading, success, and error feedback for user actions.
- Improve responsive UI behavior and layout padding.
- Ensure labels and tab headers have sufficient contrast and readability.
- Validate OTP/email delivery configuration for forgot password flow.

---

## QA Notes

Each issue includes reproduction steps and evidence links to help developers verify and resolve the bug efficiently. High-priority issues should be addressed first, especially those related to authentication, cart/order behavior, access control, and server-side errors.

---

## Author

**Abidur Rahman Sourov**  
QA / Manual Tester
