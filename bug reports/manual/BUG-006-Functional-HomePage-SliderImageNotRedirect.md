# 🐞 Bug Report: Slider Image Click Does Not Redirect

## Bug Report ID: BUG-006  
## Test Type: Functional  
## Module: Home Page  

## 🧪 Test Case:
- **Test Case ID**: TC_HP_032  
- **Test Scenario**: Verify that clicking on a slider image redirects to the correct page.

## ✅ Steps to Reproduce:
1. Open the home page of the website.
2. Locate the image slider.
3. Click on any of the slider images.
4. Observe the result.

## 🔄 Expected Result:
Clicking on a slider image should redirect the user to the relevant content or product page associated with that image.

## ❌ Actual Result:
Clicking on slider images produces no action. No redirection occurs, and the user remains on the same page.

## 📝 Notes:
- Issue observed on Google Chrome (v123.0).
- This prevents the execution of test cases related to promotional or featured content navigation.
- Possibly due to missing `href`, broken JavaScript event, or unbound click listener on slider elements.

## ⚠️ Severity: Medium  
## 🏷️ Status: Open  

## 📎 Attachments:
- [Bug Reproduction Video](https://drive.google.com/file/d/15irmH31UmFcZzHuAp9bYDttahN7Xc9uT/view?usp=drive_link)
