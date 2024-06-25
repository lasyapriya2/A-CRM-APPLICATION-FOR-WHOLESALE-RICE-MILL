# A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL

The Rice Mill CRM Application is a comprehensive solution designed to streamline and simplify how much rice per day,how many were sold that rice and which type of rice all reports send to owners daily wise. It leverages the power of customer relationship management (CRM) to enhance customer experiences, optimize store operations, and improve overall efficiency in the rice mill factory. This project aims to develop a user-friendly and feature-rich application that addresses the specific needs of a rice mill factory.

Features and Functionality:

Reporting and Dashboards: The application can generate detailed reports and analytics regarding daily how much rice sold and total income per daily, revenue generated, popular amenities, and most buyed customers. Easy to understand the data to the owner, improving resource allocation, and planning future development.

![Rice Mill Dashboard](https://github.com/lasyapriya2/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL/assets/142497246/6cbcf5ee-58f1-4f63-9c5c-9669333024f9)

![image](https://github.com/lasyapriya2/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL/assets/142497246/b457cde5-87d5-438b-93a1-98624641f075)

A rollup summary field: This is a field that summarizes data from a child object to a parent object that shares a master-detail relationship. Rollup summary fields can use the COUNT, SUM, MIN, and MAX functions. For example, you could use a rollup summary field to display the total value (amount of rice supplied ) from rice details on a related supplier.

![consumer field](https://github.com/lasyapriya2/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL/assets/142497246/99cddc29-a439-4140-a62c-4663f0164890)

A cross-object formula field: It is a formula field that references fields from another object in Salesforce. This type of formula allows users to calculate the total amount from number of rice taken*price/kg and it displays the total amount I have to pay.

Validation rules: validation rules also include an error message to display to the user when the rule returns a value of “True” due to an invalid value.so , In this project i gave Isblank formula.Isblank formula is used to verify whether it is blank it shows error.

![validation rules](https://github.com/lasyapriya2/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL/assets/142497246/6d8df83b-d340-4fa2-9fe4-ed7de9631513)

Permission sets: Organization Wide Defaults(OWD) in salesforce is the baseline level of access that the most restricted user should have. Organizational Wide Defaults are used to restrict access.But in our case we created roles and given the roles in such a way that the owner can see employer and worker records , and the employer can see the worker records.

![Sharing Settings](https://github.com/lasyapriya2/A-CRM-APPLICATION-FOR-WHOLESALE-RICE-MILL/assets/142497246/1bd994d3-cbc1-4439-9604-a613e873e0f4)

