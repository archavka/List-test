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


#### Scope of Testing - Features not to be tested 


Is under considiration.


### Test Approachs 



#### Smoke testing

___

Purpose:   Make sure stabile builds are available before next stage of testing can start

Scope:     Basic flows, entire site 

Method:    Manual, excel sheet. However defects will be recorded in JIRA tool

Frequency: Each day, on getting new build



#### Functional Regression Testing

___  

Purpose: Regression test all functions of the application.

Scope: Entire site, all flows.

Method: Manual test cases present in QTest and Automation scripts created in Selenium. Defects will be recorded in Jira.

Frequency: On start of testing cycle, after smoke testing is completed successfully



#### Performance Testing:

---

Purpose: Verify application can handle a load of 10,000
users with desired response time.

Scope: Navigation, login and checkout flows

Method: Test Scripts created in Load Runner

Frequency: After functional testing is completed, and no critical/blocker defect open


### Pass/Fail Criteria

* The test will be considered passed if it's all steps are executed successfully, and actual and expected resulsts are maching.
* The test case will be considered failed, if at any step the actual result does not match expected result. A defect will be logged for each failed test case.
* The test case will be considered blocked, if it cannot be executed due to a defect, for which another test case is marked failed, Or, if test data is not available

### Test Entry/Exit Criteria

| Entry Criteria | Test Team | Other Teams | Notes |
|----------------|:---------:|------------:|------:|
| Reqirement documents are signed-off |  Complited |Complited by other persons| date |
| Test Environment is set | Complited | Careing people | date |
| Access is available to enviorment, test data, tools for testing | Complited | Under  risk | date |

| Exit Criteria | Test Team | Other Teams | Notes |
|----------------|:---------:|------------:|------:|
| All test cases are executed | To be done when is done | | date |
| 95 % test cases are passed  |  | People who care | date |
| No critical or blocker defect is open  |  |  | date |

### Test Deliverables

The following metrics will be shared amon high trust individuals and organisation as well.

| Report | Decription | Frequency |
|--------|:----------:|----------:|
| Test Execution Status | % of complitness along with listing of all defects logged| Every now and then |
| Effort Report | Effort diary |   More better |
| Project Status Report | Project reporting shared with individuals mentioned above and not only | day by day |

### Test Suspention/Resumption Criteria

Will not bet suspended If at least one of individuals is still involved. Testing resumption depends on various factors that cannot be defined yet.

### Staffing/Training needs.

The team is not trained, lack of unison between individuals and each individuals wolfes. Every day, day by day, sometimes it can be tuesday 5 o'clock.

## Risk And Mitigation

### Test Risks/Issues

| Risk         | Probability      | Impact | Mitigation plan |
|--------------|:----------------:|------:| ------:|
| col 1 is | High/Low  | High/Low | |
| col 2 is | High/Low  | High/Low | |
| col 3 is | High/Low  | High/Low | |

## Test Enviorment and Infrastructure

### Required Infrastructure

Virtual Machines with Windows 10 OS and Chrome, Firefox, Internet Explorer
Browsers (latest versions) should be available to each tester. Mobile devices, Android
and iPhone (latest OS versions) should be available

### Availability Plan

A day before today, a day ahead tomoow. 

## Roles and Responsibilities

### Roles and Assigned Responsibilities

| Role            | Responsability   |
|-----------------|:----------------:|
| Project Manager | High/Low  |
| Test Lead       | High/Low  |
| Test Team       | High/Low  |


