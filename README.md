# 🧪 E-Commerce Search & Product Page QA Testing Project

## 📌 Project Requirements
You have a thermos product-selling e-commerce platform. Now, the client wants to implement a new feature, "Search". During the client meeting, they mentioned they wanted to make the search dynamic, with any keywords or specific text. Now you have a chance to get into more details on the feature. You can ask the client up to 10 questions. List the questions according to priority and add your feedback.

Write down the test cases according to your questions and feedback.

Let's say, your development team implemented the feature on the  Evershop site (https://demo.evershop.io/). Now execute your test case in the URL and generate a report.

Now there is a happy path journey for searching with the text ”Stainless Steel Thermos”. For the first item on the list, add a couple of black/white products to your cart. Then verify the Cart. Now execute the journeys from both the API and UI. Now provide feedback on your test analysis, and keep logs of the defects.

## 📌 Project Overview

This repository contains Software Quality Assurance (SQA) artifacts created for testing and reviewing an e-commerce application. The project demonstrates practical QA skills including:

- Requirement Analysis
- Test Case Design
- UI/UX Review
- API Testing
- Bug Reporting
- Performance Testing
- Compatibility Testing

The project was performed on the EverShop demo application and focuses primarily on:

1. Search Functionality Testing
2. Product Detail Page Review
3. API Validation
4. Defect Reporting

---

## 📂 Project Deliverables

### 1️⃣ Requirement Analysis & Priority Questions

Prepared requirement clarification questions for the Search Feature covering:

- Search functionality
- API security
- User Interface behavior
- Performance expectations
- Cross-browser compatibility
- Mobile responsiveness

#### Key Areas Covered

- Keyword search
- Partial keyword search
- Brand search
- Category search
- SKU search
- Auto-suggestions
- Search history
- Search API validation
- Response time requirements
- Browser compatibility

---

### 2️⃣ Test Case Design

Designed comprehensive test cases for the Search Button functionality.

#### Test Coverage

✅ Functional Testing

- Exact keyword search
- Partial keyword search
- Case-insensitive search
- Empty search handling
- Invalid search handling

✅ UI Testing

- Search bar visibility
- Placeholder validation
- Auto-suggestion alignment
- Highlighted search terms

✅ Compatibility Testing

- Chrome
- Firefox
- Edge
- Safari

✅ Responsive Testing

- Desktop
- Tablet
- Mobile

---

### 3️⃣ Product Page Review (UI & API Feedback)

Performed usability review for the **Stainless Steel Thermos** product page.

#### UI Improvement Suggestions

- Multiple product images from different angles
- Product image zoom feature
- Better placement of delivery information
- Return & warranty section visibility
- Payment method visibility
- Live chat/Q&A section
- Customer review section
- Improved Add to Cart and Buy Now buttons

#### API Review

Validated product-related APIs:

| API | Method |
|-------|----------|
| Product Details | GET |
| Product Variant | GET |
| Cart | GET |
| Checkout | GET |
| Order Success | GET |

---

### 4️⃣ API Testing

API testing was performed using Postman.

#### Verification Areas

- Response Status Codes
- Response Body Validation
- Data Consistency
- API Security Considerations
- Endpoint Accessibility

---

### 5️⃣ Bug Reporting

Reported multiple defects identified during testing.

#### Sample Bugs

### TK-01
**Title:** Search suggestion not appearing for typo keyword

**Steps:**
1. Search "tharmos"
2. Observe results

**Expected:**
System should provide "thermos" suggestion.

**Actual:**
No suggestion displayed.

---

### TK-03
**Title:** Inconsistent keyword highlighting

**Expected:**
All matching keywords should be highlighted consistently.

**Actual:**
One keyword highlighted while another matching keyword is not.

---

### TK-04
**Title:** High page loading time

**Observation:**
Performance issue detected during loading.

---

### TK-05
**Title:** Slow loading on 3G Network

**Result:**
Page loading time observed at 4.23 seconds.

---

## 🔧 Testing Techniques Used

- Black Box Testing
- Functional Testing
- UI Testing
- Exploratory Testing
- API Testing
- Performance Testing
- Compatibility Testing
- Responsive Testing

---

## 🛠 Tools Used

| Tool | Purpose |
|--------|-----------|
| Postman | API Testing |
| Excel | Test Case Documentation |
| Microsoft Word | Requirement & Bug Documentation |
| Chrome DevTools | Performance Testing |
| EverShop Demo | Test Environment |

---

## 📊 Skills Demonstrated

- Requirement Gathering
- Test Planning
- Test Case Writing
- Bug Reporting
- API Validation
- UI/UX Analysis
- Performance Evaluation
- Documentation

---

## 🎯 Objective

The goal of this project is to showcase practical Software Quality Assurance skills through real-world testing activities, covering both functional and non-functional aspects of a modern e-commerce application.

---

## 👨‍💻 Author

**Mahbubul Islam**

Software Quality Assurance (SQA) Engineer

- Manual Testing
- API Testing
- Test Case Design
- Bug Reporting
- QA Documentation

GitHub: https://github.com/mahbubfaisalcse

LinkedIn: https://www.linkedin.com/in/mahbubfaisal/

---
⭐ If you found this project helpful, feel free to star the repository.
