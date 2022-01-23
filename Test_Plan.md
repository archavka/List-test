# Test Plan

Name of org: List.am  
Version 1.0  
Status: Draft


## Introduction

This document decribes the testing approach to List.am. The test plan  supports following objectives:

* Test strategy
* Test execution strategy
* Test management

## Test Item

### Project Description

It's lunched and functioning. The project involves testing support for this website, mobile site and its App. The project spans entire platform List.am. Info available anytime, anywhere.


### Items to be tested/not tested

#### Scope of testing - Features to be tested 

All features that are defined in requirment document are to be tested.


| Item to Test   | Time required | Assigned to   | Current Status | Finished | 
|----------------|---------------|---------------|----------------|-----------|
| Website layout and general navigation | Functional testing will be performed to check the general flow of application  |  | in progress | - [x] ok?
| Checkout and payment modules | Ability to purchase a course, make online payments  |  | in progress | [x] item1<br/>[ ] item2
| Account module   | Ability to create an account, login and view account details, including past purchases  |  | in progress | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul>
| Performance Testing   | Load testing with 10,000 users  |  | in progress | <ul><li>[x] item1</li><li>[ ] item2</li></ul>


- [x] works
- [x] works too
- [ ] prosto

### Test Approachs 

#### Smoke testing

Purpose:   Make sure stabile builds are available before next stage of testing can start
Scope:     Basic flows, entire site 
Method:    Manual, excel sheet. However defects will be recorded in JIRA tool
Frequency: Each day, on getting new build
