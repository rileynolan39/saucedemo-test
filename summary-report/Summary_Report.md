# Test Summary Report – SauceDemo

## 1. Overview
This document summarizes the results of manual testing performed on the SauceDemo web application.

## 2. Test Execution Summary
- Total Test Cases: 123
- Passed: 99
- Failed: 24

- Group 0 Test Cases: 24
- Passed: 24
- Failed: 0

- Group 1 Test Cases: 3
- Passed: 3
- Failed: 0

- Group 2 Test Cases: 24
- Passed: 11
- Failed: 13

- Group 3 Test Cases: 24
- Passed: 24
- Failed: 0

- Group 4 Test Cases: 24
- Passed: 14
- Failed: 10

- Group 5 Test Cases: 24
- Passed: 23
- Failed: 1

## 3. Defect Summary
- Total Defects: 24
  - High: 11
  - Medium: 4
  - Low: 9

- Group 0 Defects: 0
  - High: 0
  - Medium: 0
  - Low: 0

- Group 1 Defects: 0
  - High: 0
  - Medium: 0
  - Low: 0

- Group 2 Defects: 13
  - High: 6
  - Medium: 2
  - Low: 5

- Group 3 Defects: 0
  - High: 0
  - Medium: 0
  - Low: 0

- Group 4 Defects: 10
  - High: 4
  - Medium: 2
  - Low: 4

- Group 5 Defects: 1
  - High: 1
  - Medium: 0
  - Low: 0

## 4. Key Issues Identified
- Group 0 Issues:
  - Everything is working correctly, though the ability to checkout with an empty cart seems like unintended functionality that should be addressed

- Group 1 Issues:
  - User lockout function is working correctly but the error message could provide more information on how a user can unlock their account

- Group 2 Issues:
  - Incorrect images on product page
  - Sorting broken on products page
  - Item links redirect to incorrect pages
  - Some items can not be added to cart
  - Items can not be removed from cart from product page or item pages
  - Text box issues on checkout information page make check out impossible

- Group 3 Issues:
  - Page is functional but long load times during certain actions should be addressed.

- Group 4 Issues:
  - Sorting broken on products page
  - Some items can not be added to cart
  - Items can not be removed from cart from product page or item pages
  - Text box issues on checkout information page prevents valid information from being submitted
  - Proceeding to final checkout possible with no valid last name
  - Final checkout not possible due to broken "Finish" button

- Group 5 Issues:
  - Incorrect image on products page
  - Prices incorrect on products page

## 5. Recommendations
- Fix defect before release
- Improve input validation

## 6. Conclusion
- Group 0 Conclusion:
  The application is overall functional and there should be little issue with adding the necessary checks to checking out before product launch.

- Group 1 Conclusion:
  User lockout function is working correctly and there should be little issue in editing the error message to be more helpful to locked out users before product launch.

- Group 2 Conclusion:
  Many significant issues present that make the prodcut unviable. Could take significant time to fix all issues before product launch.

- Group 3 Conclusion:
  The application is overall functional but the performance is lackluster. Fixing performance is recommended, if possible, before release.

- Group 4 Conclusion:
  Many significant issues present that make the prodcut unviable. Could take significant time to fix all issues before product launch.

- Group 5 Conclusion:
  The application is overall functional but there exist a small number of visual issues. These need to be addressed before product launch but the nature of these issues should make them relatively easy and quick to fix.