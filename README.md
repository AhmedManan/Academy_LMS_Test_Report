# Academy LMS (WordPress Plugin) Test Report

Welcome to the Test Report for the [Academy LMS (WordPress Plugin)](https://academylms.net/) by Kodezen. This document provides a comprehensive overview of the testing process, test metrics, Test Cases, and Bug Reports related to the plugin.

## Table of Contents
- [Introduction](#introduction)
- [Features Tested](#features-tested)
- [Test Metrics](#test-metrics)
- [Test Cases](#test-cases)
- [SQA Mind Map](#sqa-mind-map)
- [Bug Report](#bug-report)

## Introduction
Academy LMS, is a next-generation, fastest WordPress LMS plugin, that will improve your online learning experience. It has seamless integration with any WordPress site allowing you to easily create and sell engaging online courses. With a user-friendly interface and lightning-fast performance, you can transform your website into a professional e-learning platform in no time. https://wordpress.org/plugins/academy/

## Features Tested
I have thoroughly tested the following modules of the WordPress plugin:

1. **User Sign In**
   - Ensure different roles users log in.
   - Verify login confirmation process.

2. **Instructor Registration**
   - Confirm users can be registered with valid credentials.
   - Verify registered users need admin approval.
   - Ensures new users can't register with registered email & usernames.

3. **Student Registration**
   - Confirm users can be registered with valid credentials.
   - Ensures new users can't register with registered email & usernames.

4. **Academy LMS Admin Panel**
   - Test various features of the Academy LMS Admin Panel
   - Test woo commerce integration
   - Test with various themes plugins

## Test Metrics
During the testing process, we collected the following metrics to evaluate the quality of the User Management Module:

- **Percentage of Test Case Executed:** 100%
- **Test Cases Executed:** 13 out of (*not defined yet)
- **Pass Percentage:** 30.76%
- **Fail Percentage:** 69.23%
- **Percentage of Test Case Blocked:** 0%
- **Bug Severity Distribution:** (See Bug Report Section)

## Test Cases
We have designed and executed a set of test cases to validate the functionality of the User Management Module. Here are some representative test cases:

***(Section To Be Continued)***

For a complete list of test cases, please refer to the [Test Case Documentation](Academy_LMS_Kodezen.xlsx).

## SQA Mind Map
![SQA Mind Map](Mindmap/mindmap.png)

***(Section To Be Continued)***

## Bug Report
I have discovered and documented several bugs during our testing phase. Here is a summary:

| Bug ID | Description | Screenshot / Screen Record|
| ------ | ----------- | -------- |
| BUG-001 | The Click option doesn't work on hovering over the Navigation Bar. | [Bug_1](https://drive.google.com/file/d/1kKTm7UH58tEilNqT-8reKMTJHjzApocS/view) |
| BUG-002 | Navigation Bar alignment breaks on Dashboard Page. | [Bug_2](https://github.com/AhmedManan/Academy_LMS_Test_Report/blob/main/Screenshots_%26_Screen_Records/bug_05.png) | 
| BUG-003 | Invalid ration of Admin Commision Percentage & Instructor Commision Percentage, Sum of the percentage exeeds 100%. | [Bug_3](https://drive.google.com/file/d/1diCYo16Bi2_cztWFdGoDZsuBoMhwTVu5/view) | 
| BUG-004 | Invalid condition for Fee Deduction Amount & Fee Deduction Type. Fees Deduction Type can't be Percentage when Fee Deduction Amount is set to more than 100. | [Bug_4](https://drive.google.com/file/d/1gT9IGQ6vcQ7Ktbh8zqxfF3NUUC0xsEuW/view) |
| BUG-005 | Necessary fields in the Instructor Registration & Student Registration are not properly validated | [Bug_5](https://drive.google.com/file/d/1BRGJYUUI7q_Ql_mx6MCTydkJ-6y-1Fir/view) | 
| BUG-006 | Instructor Registration & Student Registration are not showing a proper message for a already registered user. | [Bug_6](https://drive.google.com/file/d/1pqjOMl13I7v5cFUDs4Ne2nu6cv_5-rEL/view) | 

For more details about each bug, please refer to the [complete Bug Report](RFL_Best_Buy.xlsx).

---

This Test Report provides an overview of our testing process, test cases, and the status of the Sign In / Login, Student Registration, Instructor Registration, and Academy LMS Admin Panel Module. Feel free to reach out for any questions or clarifications.

**You Can Also See:** [Manual Test Report Of RFL Best Buy](https://github.com/AhmedManan/Manual_Test_RFL_BestBuy)

**Read My Blogs:** [Manan's Blog](https://ahmedmanan.com/blog/)

[⬆️Back to Top](#academy-lms-wordpress-plugin-test-report)

