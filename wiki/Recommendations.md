# Introduction
The current technology landscape, business processes and constraints around data / MI are reminiscent of the way service based organisations ran contact centres 15-20 years ago. If the FSA are serious about providing consistently high standards of customer service - which we believe they are based on the stakeholders we've engaged with and the feedback gathered from them - then the following recommendations will provide a solid foundation for doing so whilst also allowing the FSA to plan for future iterations of the Helpline service.

# Technology
## **Replace the existing Avaya telephony system**

A modern, cloud based telephony platform will provide the following business critical capabilities not provided or configured on the current Avaya platform;

- Ability to configure remotely (call routing, invocation of emergency closures)
- Provision of a robust Disaster Recovery / Business Continuity capability and the ability for the Helpline team to handle calls remotely through use of softphones & CTI (the current solution relies on Hunt Groups routing calls to the mobile phones of Helpline team members which carries a number of risks and removes the ability to report on telephony and agent activity)
- Ability to blend telephony with other service channels. At the moment this would include email, however, modern telephony platforms will also support blending of digital service channels.

This does not prevent the continued iteration of the IVR options recently implemented as the set of options in use at the time of migration will simply be configured on the new telephony platform of choice.

## **Introduction of a “lite” enquiry management system**
The introduction of a lightweight CRM or enquiry management system for the Helpline team as well as other specialist support teams will provide a number of benefits. It goes without saying that whichever solution is decided upon that it should be cloud based to support remote working and include the provision of API's to support integration with the telephony platform, Power BI and any other requisite line of business systems. It will master Helpline contact and enquiry data with information recorded in a single place. From a business process perspective this will reduce waste & inefficiency by providing a unified user interface for teams to work from - mitigating all current manual workarounds and tasks - whilst also supporting better collaboration between teams by providing a quicker and easier way to share enquiry information. Additionally, most modern platforms provide inbuilt tools that can be configured to support SLA monitoring and escalations - again, all within a single tool which is not currently the case - with key benefits being reduced time for enquiry resolution, improved first contact resolution (FCR) and higher levels of customer satisfaction.

When considering the future state of the Helpline Service, a modern CRM / Enquiry management system will support the integration of digital service channels, all within the single user interface.

In line with this, we recommend the FSA expands the existing requirements to include both current and future needs, focusing on user needs, functional capabilities & MI / data requirements. Whilst the future state of the Helpline Service has not yet been clearly defined, including high level functional capabilities such as the ability to support digital service channels such as web chat, social customer service etc, will provide a degree of future proofing when choosing a solution.

# Data
## **Define the underlying data needed to deliver an effective Helpline service**

Defining the core underlying data model will be key to supporting day to day operations as well as providing richer MI. We have established three key elements that we believe will support the delivery of high quality service as well as rich MI. Although not exhaustive, the following provides a foundation on which the FSA can refine as part of expanding the current Helpline Service requirements;

**Contact information**
- title, initial, first name, surname, company name
- telephone number
- email address
- address
- post code

**Enquiry information**
- enquiry type
- enquiry reason
- enquiry description
- team enquiry is assigned to
- enquiry response 
- Enquiry status

**Operational information (service channels, service levels, escalations, FCR etc)**
- service level adherence (i.e. responded to within / outside 20 days)
- telephony data (total calls offered / handled, % of calls answered, % of calls abandoned, % of calls answered within xx seconds)
- email data (total emails received, date received, date responded, enquiry response)
- total enquiries received today / yesterday / last week / last month / last year
- total open enquiries
- total in progress enquiries
- total closed enquiries today / yesterday / last week / last month / last year
- total enquiries closed per user today / yesterday / last week / last month / last year
- Volume / % of enquiries closed within SLA (overall, by service channel, by team and by user)
- Volume / % of enquiries not closed with SLA ((overall by service channel, by team and by user)
- total volume of escalations
- FCR (first contact resolution) rate 
- Enquiry type / reason received today / yesterday / last week / last month / last year
- Customer satisfaction scores

Consolidation of customer and enquiry data into a single application will support faster and easier production of MI because a modern CRM / Enquiry Management solution will provide easy access to data through API's which your existing data visualisation tool (PowerBI) can leverage.

## **Consider future data needs**
The above is really about putting the data and reporting foundations in place so that the FSA can use MI to determine how well the Helpline Service is operating and take appropriate, corrective action where needed to ensure a consistently high level of service is provided to its customers. Looking forward, the FSA should consider how you can use Helpline Service data to proactively manage the service and drive enhancements. Some examples that are commonly considered across service organisations includes the mitigation of repeat contacts, proactive issue identification and resolution, resource planning & contact deflection / self service).

## GDPR
Compliance with GDPR is a must for any organisation capturing PII from individuals interacting with the organisation. Further information can be found here [document](https://www.privacy-regulation.eu/en/article-5-principles-relating-to-processing-of-personal-data-GDPR.htm). 

The Helpline & Customer Contact Squad have reached out to the data team for evidence of the FSA's GDPR compliance and, whilst we have been assured that GDPR compliance is not an issue, due to resource issues within the data team a response was not forthcoming before the Discovery ended. Once received, the Product Owners should assess whether the data captured as part of the delivery of the Helpline Service is compliant and, if applicable, identify areas for of non-compliance and mitigation strategies as part of the expansion of the Helpline Service requirements.

Related to this are the FSA's retention schedules which can be found here http://fsahome/how/info/Documents/corporateretentionschedules2.0.pdf

## Final Report
**The final report presented during playback on Monday 6th April is available here**; [Uploaded file](uploads/Helpline__Customer_Contact_Final_Report_V1.3.pdf)

## Lightweight Enquiry Management solutions
In the report and during discussions we recommend the introduction of a lightweight solution for the management of enquiries. A list of those can be viewed here https://www.capterra.com/contact-management-software/

