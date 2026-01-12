# 🕵️ Professional Bug Log: SauceDemo
**Tester:** Vanessa Anderson 
**Focus:** Manual Functional Testing & Edge Cases

---

## Bug ID: 001 | Broken Product Images
(Paste your Bug 001 details here...)

---

## Bug ID: 002 (Ref: #2) | Checkout Allowed with Empty Cart...

---

## Bug ID: 003 | First Name Field Text Overflow
...

---

## Bug ID: 004 | Incorrect Asset Rendering (Problem User)
...# 🕵️ Professional Bug Log: SauceDemo
**Tester:** Vanessa Anderson 
**Focus:** Manual Functional Testing & Edge Cases

---

## Bug ID: 002 | Checkout Allowed with Empty Cart
**Severity:** Medium | **Type:** Functional Logic

**Description:** The application allows a user to proceed to the "Checkout: Your Information" screen even when the shopping cart contains zero items.

**Steps to Reproduce:**
1. Navigate to https://www.saucedemo.com/
2. Login as `standard_user`.
3. Click the Shopping Cart icon (verify it is empty).
4. Click the "Checkout" button.

**Expected Result:** The user should be prevented from checking out. The "Checkout" button should be disabled, or an error message should appear stating "Your cart is empty."

**Actual Result:** The system ignores the empty cart status and navigates the user to the checkout information page (`/checkout-step-one.html`).

---## Bug ID: 003 | First Name Field Text Overflow
**Severity:** Low | **Type:** UI/Visual

**Description:** The "First Name" input field does not have a character limit or proper text-wrapping. Entering a long continuous string causes the text to overflow the visual boundaries of the input box.

**Steps to Reproduce:**
1. Login as `standard_user`.
2. Add an item to the cart and proceed to Checkout.
3. In the "First Name" field, paste a string of 100+ characters without spaces.
4. Observe the text alignment.

**Expected Result:** The text should either be limited to a maximum character count (e.g., 50) or remain contained within the visible box.
**Actual Result:** The text overflows the input line and creates a messy visual experience.

## Bug ID: 003 | First Name Field Text Overflow
**Severity:** Low | **Type:** UI/Visual

**Description:** The "First Name" input field does not have a character limit or proper text-wrapping. Entering a long continuous string causes the text to overflow the visual boundaries of the input box.

**Steps to Reproduce:**
1. Login as `standard_user`.
2. Add an item to the cart and proceed to Checkout.
3. In the "First Name" field, paste a string of 100+ characters without spaces.
4. Observe the text alignment.

**Expected Result:** The text should either be limited to a maximum character count (e.g., 50) or remain contained within the visible box.
**Actual Result:** The text overflows the input line and creates a messy visual experience.

---

## Bug ID: 004 | Incorrect Asset Rendering (Problem User)
**Severity:** Medium | **Type:** Functional / Visual

**Description:** When logged in as `problem_user`, all product inventory images fail to load correctly and are replaced by a placeholder/dog image. This occurs on both Desktop and Mobile views.

**Steps to Reproduce:**
1. Open SauceDemo.com and toggle Mobile Emulation (iPhone/Pixel).
2. Login as `problem_user`.
3. Observe the inventory page product images.

**Expected Result:** Each product should display its unique, correct image.
**Actual Result:** All products display the same incorrect dog image.