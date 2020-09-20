# Group Sense Solutions COVID-19 Testing Program
Cassidy Mentus, Nishant Shukla, Marty Romeo, Christian DiPaola

## Notice: 
**We are no longer offering or building our testing program. Thank you to our collaborators for their hard work and dedication. Although we are closing up shop, our project has had a lasting impact on fighting the pandemic. We have, with other anti-pandemic activism groups, alerted US federal COVID-19 task force of testing capacity in academic and CORE labs and leading to temporarily lifted restrictions on testing. Our research has helped lead to the approval and use of group testing for high through-put and turn around testing. We are proud to have consulted for: CDC, Medical University of South Carolina, Vanderbilt University, Institute for Immunology and Infectious Diseases (Western Australia), NFL, SpaceX.**

**We hope this webpage can be used as a reference for future testing programs. Please cite any documents or presentations on the website if you use them. If you have questions please email cassidy.mentus@gmail.com**

## Website Structure
In this website you will find:
* Plans for a work flow using self-administered saliva collection and linking to samples using QR codes designed to protect privacy. We describe an app where lab personnel can track QR code-labeled samples and record + electronically send out results. This is designed for high through-put hassle-free tests and is meant to get academic labs into the front line of testing.  You can read this off this page or click on the link to a pdf/slide deck in the contents. 

* Research: We have researched pooled testing using ddPCR.  Pooled testing occurs in 2 rounds, but we have researched ways to complete testing in **one round** of testing. For example, if one QX200 can test 90 wells in one round, then our method allows it to test **~600** samples in one pooled round followed by confirmatory tests. It is theoretically possible to shorten this to one round (600 people with one round of testing on a machine that normally can only do 90) if we use reconstruction techniques from compressed sensing with Poisson noise.

Our research also estimates the sensitivity at each viral concentration and demonstrates ease of use of our pooling app.


## Contents
* [Program Details](GSS-COVID19-program.pdf)
* [Slide Deck](GSS-COVID19-program.pdf)
* Research:
    * [Recent Research Summary](grant_summary_8-13.pdf) - Includes introduction to pooled testing. Assay sensitivity analysis using real saliva samples with Poisson regression. Introduction to compressed sensing. 
    * Compressed sensing using droplet digital PCR. [Technical Paper Draft](https://github.com/cmentus/ddPCR-compressed-sensing/blob/master/PCR_CS_cmentus9-3.pdf) [github for code](https://github.com/cmentus/ddPCR-compressed-sensing)
    * [Droplet digital PCR assay for COVID-19](https://www.medrxiv.org/content/medrxiv/early/2020/05/11/2020.05.06.20090449.full.pdf)
    * [Expository paper for basic pooled testing methods](https://www.medrxiv.org/content/medrxiv/early/2020/04/16/2020.04.05.20050245.full.pdf)  We only recommend this binary splitting if groups or 4-8 are used for the sake of turn-around. It is nearly optimal in terms of test-kit usage.

# Statement of Purpose
We provide a streamlined system for COVID-19 testing using the most sensitive RNA-based assay found in academic and CORE research labs, Droplet Digital PCR (ddPCR).  Our system is engineered to solve the problem of testing asymptomatic populations accurately, frequently.  
	The world is in unique and unprecedented times.  We understand that your needs as a business or community are unique and evolving. We will help craft a customized strategy that fits your needs and can adapt as circumstances require. Our main purpose is to help your organization develop a custom-tailored strategy that balances your unique needs with respect to key components of testing program design:

1. Throughput-How many tests that can be processed in a given amount of time.
2. Sensitivity/accuracy-Not all tests are created equal. 
3. Predictable result delivery-If labs results are not timely the information may not be useful. Lab and health systems are stressed.  Large clinical diagnostics companies are not always meeting timing demands. 
4. Cost/Resource Utilization: Our group/pool testing strategy can help drive efficiency in this regard. 
5. Time savings- After being shipped overnight or same-day, tests are immediately carried out. The same lab personnel testing your sample uses our system to notify you about results as they are read off the machine. Unnecessary steps are eliminated.

## How Do We Achieve These Goals?
* Specimen tracking from collection to result delivery utilizing our customizable HIPAA compliant software system
* Ease and comfort of self-administered saliva sample collection: Minimizes need for additional collection sites and staffing. 
* We have partnered with several of the most innovative medical center core molecular biology labs in the country to deliver these lab testing services. 
* We have partnered with BioRad Inc. to deliver the highest sensitivity PCR system in the world for the most sensitive results available.

# COVID-19 Testing Program Outline

Our COVID-19 testing program is operationalized by our app and data system. The app has portals for patients, medical staff/coordinators and the lab personnel performing the tests. It keeps track of sample inventory, manages laboratory information and reports results.

**Step 1:** Saliva collection kits are labeled with randomly generated QR codes and delivered to your location. 
Notes: 
·	Saliva collection kits are for self-administration.  
·	Kits are designed to deactivate preserve specimens for months without refrigeration. They will easily withstand transportation to labs.
·	After kit is sealed, it can be safely handled without risking exposure.

**Step 2:**  Identifying information and sample information including the test result are stored on two separate databases. This guards patient identity and is HIPAA compliant.

**Step 3:** Each person produces a saliva specimen and brings it to the site coordinator.  Specimens are shipped to our partner research lab.

**Step 4:** Sample tubes are scanned by lab personnel using our app. The app will then generate instructions for your test method of choice.

**1:1 tests:** Each sample is assayed on its own for a test that is ~20x more sensitive than qPCR tests that are typically used by large commercial diagnostic 

**2-stage group testing:** The samples are combined into pools for group tests. If the prevalence is low, this uses 45%-80% less test kits than 1:1 testing. Group testing algorithms are designed using current mathematical literature and sensitivity specific to ddPCR. 

