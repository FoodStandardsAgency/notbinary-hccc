# Technologies
## Within Helpline England

### Paper
As mentioned in the user research section it happens that Helpline agents keep a paper physical copy of a query. This copy is said to be stored safely, but never reviewed to find if the data is still accurate or is it due for deletion.

### K2
[K2](help.k2.com) is the current system Helpline England uses to record and treat enquiries. It has been used for about 2 years so far. 
An example of usage is: On a weekly basis a spreadsheet of calls that have been open for 10 days or more since the initial call are sent to respective departments using SQL Server Reporting Services (SSRS) (reporting tool over the top of SQL tables that K2 writes to) copied to the help desk.
In terms of usage England Helpline are the primary users of this tool. The policy team for example is not using K2, nor the other regions.
K2 is used in WATOK but it is a different interface and different database.
Accessibility
Anyone who has an FSA account could have access to K2 and therefore close the assigned to them cases. The helpline team does not need to chase these teams as the responsibility for the query goes to the assigned team.

Business continuity, both for phone and emails, needs to be assured in situations like today where it is advised to work from home to lower the employees health risks.

It is important to note that K2 has more features, but that have not been implemented yet in the currently used K2 version within FSA. The team that originally implemented the K2 system has moved into another department and priorities of this department were different than the K2 system.

### Power BI
[Power BI](https://powerbi.microsoft.com/en-us/) is a business analytics service by Microsoft. It aims to provide interactive visualisations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards. It is the Data analytics tool used by FSA across regions, not only for the teams using K2. Indeed Power BI and K2 and tightly coupled in the current architectural implementation, but it is widely used on its own as well.
It mainly helps to visualise the data and contributes into report writing.


## Other
Each public facing region within the FSA chooses systems and processes to deal with the incoming queries independently of other regions. In this section there are described some of the other systems used within FSA to treat queries. There is currently no alignment between the different regions.

### Wisdom
[Wisdom](https://www.wisdom.co.uk/) is the chosen system for Northern Ireland and Wales teams. 

### eCase
Private office uses [eCase](https://www.ecase.co.uk/) - another case management system. 
