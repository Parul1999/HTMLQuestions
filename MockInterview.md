**HTML Mock Interview Questions (Advanced Level)**

## **Section 1: Rapid-Fire Conceptual Questions**

Answer in **1-2 sentences**.

1. What happens if you use `<meta charset="UTF-8">` incorrectly or omit it?
2. How does the `<template>` element work in HTML?
3. What is the default behavior of the `<button>` tag inside a form?
4. What does the `novalidate` attribute do in a `<form>`?
5. Why should we use `aria-labelledby` instead of `aria-label` in some cases?
6. How does `<datalist>` improve form usability?
7. What is the difference between `<abbr>` and `<acronym>`?
8. When should you use `<wbr>` inside a word?
9. Why is the `ismap` attribute used in `<img>`?
10. What happens when you place an `<input>` element outside a `<form>`?
11. What happens when you set `contenteditable="true"` on an element?
12. How is `noscript` used in an HTML document, and when is it useful?
13. What does `translate="no"` do in an HTML tag?
14. How can you disable right-clicking on a webpage using only HTML?
15. What is the difference between `<output>` and `<span>` in a form?
16. What does `draggable="true"` do in an HTML element?
17. How can you create a modal pop-up using only HTML?
18. What is the difference between `<time>` and `<datetime>` attributes?
19. Why does `<iframe>` sometimes fail to load external websites?
20. What happens if you use `spellcheck="false"` inside an `<input>` field?
21. What happens if a `<fieldset>` is used inside another `<fieldset>`?
22. What is the purpose of the `accept` attribute in an `<input type="file">` element?
23. How does `autocapitalize` help in an `<input>` field?
24. What is the difference between `placeholder` and `label` in forms?
25. Can a `<form>` have multiple `<fieldset>` elements? Why or why not?
26. What does `dir="rtl"` do in an HTML document?
27. Why should you use `<mark>` instead of `<b>` for highlighting important text?
28. What is the difference between `hreflang` and `lang` attributes in an `<a>` tag?
29. Why is the `<output>` element useful in forms?
30. What is the difference between `<kbd>`, `<samp>`, and `<code>` in HTML?

---

## **Section 2: Scenario-Based Coding Challenges**

Solve these **real-world problems** using **only HTML**.

### **Q31: Ensure a Form Field Accepts Only Specific Values**

You need an input field that **only allows usernames between 5-10 characters** (letters & numbers only).\
✅ **Write the correct HTML using the **``** attribute.**

---

### **Q32: Create a Dropdown with a Searchable Suggestion List**

You need a dropdown where users can **search and pick from predefined options** (without JavaScript).\
✅ **Write the correct HTML using **``**.**

---

### **Q33: Mark Up a Time-Sensitive Event Using the Correct Element**

You need to display **"Meeting on March 5, 2024, at 3 PM"** in a way that **helps browsers understand the date/time**.\
✅ **Write the correct HTML using **``**.**

---

### **Q34: Create an Accessible Skip Navigation Link**

Users should be able to **skip directly to the main content** when pressing `Tab`.\
✅ **Write the correct HTML.**

---

### **Q35: Fix a Form That Submits Even When Fields Are Empty**

The following form **submits even if fields are empty**:

```html
<form>
  <input type="text" name="username">
  <input type="email" name="email">
  <button type="submit">Submit</button>
</form>
```

✅ **Fix it so both fields are required.**

---

## **Section 3: Debugging & Problem-Solving**

Analyze and **fix the issues** in the following HTML snippets.

### **Q36: Why Is the Required Field Not Triggering Validation?**

```html
<input type="text" required value="">
```

❌ **Issue:** The browser **does not show a validation error** even when empty.\
✅ **Find the issue and fix it.**

---

### **Q37: Fix an **``** That Fails to Load on Slow Connections**

```html
<img src="image.jpg">
```

❌ **Issue:** The image **takes too long to load** on slow connections.\
✅ **Fix it using HTML attributes.**

---

### **Q38: Why Does This **``** Not Work on iOS?**

```html
<input type="date">
```

❌ **Issue:** The **date picker does not appear** in Safari on iPhones.\
✅ **What is the correct HTML-only fix?**

---

### **Q39: Fix the Missing Table Headers for Screen Readers**

```html
<table>
  <tr>
    <td>Product</td>
    <td>Price</td>
  </tr>
  <tr>
    <td>Phone</td>
    <td>$500</td>
  </tr>
</table>
```

❌ **Issue:** The **table headers are not marked properly** for screen readers.\
✅ **Fix it using only HTML.**

---

### **Q40: Securely Open a Link in a New Tab**

You have a link that **opens in a new tab**:

```html
<a href="https://example.com" target="_blank">Visit Site</a>
```

❌ **Issue:** This **creates a security vulnerability**.\
✅ **Fix it using only HTML.**

---



