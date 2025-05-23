# 🐞 Bug Report: No Message Shown for Already Subscribed Email

**Bug Report ID:** BUG-003  
**Test Type:** Functional  
**Module:** Home Page  
**Description:** No error or info message is shown when a user enters an already subscribed email.

---

## 🧪 Test Case

**Test Case ID:** TC_HP_006  
**Test Scenario:** Verify that the system shows a message when a user tries to subscribe with an already registered email.

---

## 🔁 Steps to Reproduce

1. Open the Home page.  
2. Enter an email address that has already been subscribed (e.g., `test@example.com`).  
3. Click the "Subscribe" button.  
4. Observe the result.

---

## ✅ Expected Result

- A clear message should be displayed, such as:  
  - "This email is already subscribed."  
  - or "You are already subscribed."

---

## ❌ Actual Result

- No message is displayed. The form gives no feedback to the user, and the subscription process appears unresponsive.

---

## 📝 Notes

- This prevents test cases related to duplicate email validation from being executed.  
- Issue was encountered in **Google Chrome**.  
- Possibly due to a missing frontend validation or unhandled backend response.

---

## 🚨 Severity

**Medium**

---

## ⚙️ Priority

**Medium**

---

## 📌 Status

**Open**

---

## 📎 Attachments

  
- [Bug Reproduction Video](https://drive.google.com/file/d/1lie_0b1LBp15GtoWCKh52WLRkc2OF5po/view?usp=drive_link)


