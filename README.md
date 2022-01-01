# Business Analyst Case Study for XYZ organization

### Case study overview: 
Invloing in a BA role to craft a software development case for a non-profit, U.S. based organization.

The overall business reuirements is discussed, and one of the business processes (User registration & matching) is selected to be demontrated in this case study
#### Table of content

- [Background](#background)
  * [Company overview](#company-overview)
  * [Business challenges](#business-challenges)
  * [Business needs](#business-needs)
    
- [Business requirements generation](#business-requirements-generation)
  * [Company background summary](#company-background-summary)
  * [Assumptions](#assumptions)
  * [Overall business requirements](#overall-business-requirements)
  * [Seleted process requirements](#seleted-process-requirements)
   
- [Business process diagram](#business-process-diagram)
  * [Current AS IS workflow diagram](#current-as-is-workflow-diagram)
  * [Future state TO BE workflow diagram](#future-state-to-be-workflow-diagram)

- [Business rules and Functional requirements-Waterfall](#business-rules-and-functional-requirements-waterfall)
  * [Business rules](business-rules)
  * [Functional requirements](#functional-requirements)

- [User persona, User Story, Acceptance Criteria-Agile](#user-persona-user-story-acceptance-criteria-agile)
  * [Happy path](#happy-path)
  * [Alternative flows](#alternative-flows)
   



<!-- toc -->

## Background


### Company overview

“XYZ organization” our client, is U.S. Based non-profit organization serving old age people worldwide to alleviate social isolation of theirs. The organization as part of the social work offers a range of services to old age people via several programs and each program is internally managed by different departments. The organization also has a pool of volunteers and social workers are the driving force behind the programs offered to old people. The client wants to develop a modern, robust, and responsive software solution that will help the internal staff to manage the associated old age people and volunteer/social worker activities program wise which includes their onboarding into the organization, their eligibility to participate or contribute which is program-specific. Internal staff will also be able to manage the departments and associated programs/services offered under each department.

### Business challenges

The client is facing an efficiency gap with the current system which requires arduous data entry and does not efficiently manage the different data sets. The end-users using the application do not want to use the current system and are looking for a well-designed new application with ease in usage. The internal staffs using the system are not very tech-savvy as well.  

### Business needs

The client needs cost-effective, robust and reliable software that could provide an effective solution for managing old age people, volunteers and social workers, departments, and programs. The client also wants the new system to generate reports (tracking activities) for senior management which will optimize analysis and strategies leading to better decision making.



## Business requirements generation


### Company background summary

About XYZ non-profit organization:

- U.S. Based non-profit organization serving old age people worldwide to alleviate social isolation
- The organization also has a pool of volunteers and social workers across the globe associated via various outreach program
- Goal:  The client wants to develop a modern, robust, and responsive software solution that will help the internal staff to manage the associated old age people and volunteer/social worker activities program wise which includes their onboarding into the organization, their eligibility to participate or contribute which is program-specific.

### Assumptions

The current system is not web-based or centralized

Data is entered manually by end-users 

- People Registered (Customers)
- Volunteers
- Social workers
- Programs

Programs/Events are published via postal mail

Volunteers/social workers only provide the service of transport to local programs

### Overall business requirements

**1. Registration / Matching local for Volunteers & Social workers(Seletecd process in the following sections)**

2. Easier mode of communication for all end-users (Customers, Volunteers, Social workers)
- Email
- Online Portal / Notifications
- Push Notifications  via App
3. Easy interface for customers to register with the organization via web
- Automated process to avoid manual data entry
4. The registration process for volunteers and social workers requires background verification 
5. Synced calendar for cancelations/ updates for customers, volunteers, and social worker 
6. Reporting ability for sr. management

### Seleted process requirements
Registration/ Matching Requirements 

- Registration for volunteers/ social workers/ senior citizens is available online (website/ mobile app)
- The main office of XYZ Organization has workstations available to fill out the application online (for volunteers/ social workers/ senior citizens)
- XYZ has Alexa Voice system to intake application via phone and provide general information
- Volunteers and Social Workers must pass a background check prior to the application getting approved
- Once the application for Volunteers/Social workers is approved, only then can they be matched with senior citizens within a 20-mile radius
- The background check includes (1) criminal background check and (2) a drug test
- Approval/ Rejections of application is communication via email or app push update for Volunteers & Social workers
- Requirement for senior citizens = 65-year-old or above, US citizen or Permanent Resident
- Once volunteers/Social workers is approved, they can be matched with up to 5 times a month
- All matches take place on the 1st Monday of a given month; Volunteers & Social workers have to provide confirmation via email or app by the 2nd Monday of a given month
- Volunteers/Social workers must be at least 18 years old in age
- Volunteers/Social workers must have a valid drivers license + personal mode of transportation
- Volunteers/Social workers must complete 10 hours of online training prior to matching


## Business process diagram


### Current AS IS workflow diagram
![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/business%20process%20diagram%20folder/AS-IS%20workflow%20diagram.png?raw=true)

### Future state TO BE workflow diagram
**The TO-BE business process diagram:**

The registration process applies to all participants of the XYZ Organization including the senior citizens, volunteers and social workers. The registration process allows XYZ organization the ability to validate and ensure the right participants are involved in the XYZ organization. Registration process differ for Senior Citizens and Volunteers/Social workers such that there are a lot more regulatory guidelines for individuals who are taking care of/supporting senior citizens and therefore, the following processes are outlined for registration for both senior citizens as well as Volunteers/Social workers.


| Senior Citizens | Volunteers/Social Workers |
| --- | --- |
| Answering qualifying questions | Answering qualifying questions |
| Fill out the registration form | Fill out the registration form |
| On-boarding process | Complete criminal background check |
| Matching process | Complete Drug test |
|  | On-boarding process |
|  | Matching process |



![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/business%20process%20diagram%20folder/TO-BE%20workflow%20diagram.png?raw=true)

## Business rules and Functional requirements-Waterfall


### Business rules

(MUST HAVE)
- Requirement for senior citizens = 65-year-old or above, US citizen or Permanent Resident
- The background check includes (1) criminal background check and (2) a drug test
- Volunteers and Social Workers must pass a background check prior to the application getting approved
- Volunteers/Social workers must be at least 18 years old in age
- Volunteers/Social workers must have a valid drivers license + personal mode of transportation

### Functional requirements

- The registration page shall have a form to capture complete information for applicant applying to be volunteer/social worker for the XYZ organization
- The system must allow a process for volunteers and social workers to pass background check prior to application getting approved
- The system must request all applicants qualifying question to validate basic requirements for participation: Senior citizens = 65+ years old, US citizen or Permanent Resident. Volunteers and Social Workers = 18+  years old, Valid Drivers License, No criminal background, No Drugs
- The system shall communicate approval or rejection of application(social workers/volunteers) via email or app push notification within 48 hours of background check + drug test

## User persona, User Story, Acceptance Criteria-Agile


### Happy path

#### Suzzie (Sr. Citizen)
![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/User%20personas%20%26%20User%20Stories/Suzzie_Sr.Citizen.png?raw=true)

Scenario: Phone call notification

Given: I am a Sr. Citizen who signed up successfully 

And: I have my phone number recorded in the system

And: I choose to have phone call notification at the preference setting 

When: There are new events updated in the system

And: new events located close to where I live within 20 miles radius

Then: I should receive a phone call notification during the organization working hours

#### Emily (Social worker)
![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/User%20personas%20%26%20User%20Stories/Emily_social%20worker.png?raw=ture)

Scenario: Background check status update

Given: I am a social worker who are signing up

And: I uploaded the required  information/documents for two rounds of background check through web/app

When: I passed both checks

Then: I should receive an email or app push up notification of the result

And: I should can start my on-boarding process

#### Peter (Volunteer)
![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/User%20personas%20%26%20User%20Stories/Peter_volunteer.png?raw=ture)


Scenario: Viewing history participation record 

Given: I am a volunteer who signed up

And: I browse “My programs” feature under my profile

When: I click on the “History” tab

Then: I should see all the historical record of the programs I attended from latest to the oldest


### Alternative flows
![alt text](https://github.com/yoyoyang91/Business-Analyst-Case-Study-for-XYZ-organization/blob/main/User%20personas%20%26%20User%20Stories/Joe_high%20school%20student.png?raw=ture)



