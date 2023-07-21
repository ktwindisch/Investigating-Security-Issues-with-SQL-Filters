<h1>Investigating Security Issues with SQL Filters</h1>

<h2>Description:</h2>

I am a security professional at a large organization. As part of my job, I investigate security issues to help keep our system secure. Recently, I discovered some potential security issues involving login attempts and employee machines.
My task is to examine the organization's data in the employees and log_in_attempts tables. I will use SQL filters to retrieve records from different datasets and investigate the potential security issues.

<h2>Environments Used:</h2>

- <b>Windows 10</b>

<h2>Investigation walk-through:</h2>

![image](https://github.com/ktwindisch/Investigating-Security-Issues-with-SQL-Filters/assets/56203054/50c79c33-349a-47db-85d4-c8858ac359ee)
- After-hours login attempts: I retrieved all login attempts that were made outside of normal business hours. The query I wrote is being used to identify all login attempts that occurred after 18:00:00 and were not successful.

![image](https://github.com/ktwindisch/Investigating-Security-Issues-with-SQL-Filters/assets/56203054/1f71d11c-8f74-4c16-b17d-17cc4a85d721)
- Login attempts outside of Mexico: I retrieved all login attempts that were made from outside of Mexico. This query is being used to identify all login attempts that did not originate from Mexico.

![image](https://github.com/ktwindisch/Investigating-Security-Issues-with-SQL-Filters/assets/56203054/3d312d7d-b885-4a8f-8e4a-8215cfaaea46)
- Here, I am collecting employee data from the Marketing department and their offices, because I am specifically looking for certain machines. The security team can then use this information to apply patches to specific systems.

![image](https://github.com/ktwindisch/Investigating-Security-Issues-with-SQL-Filters/assets/56203054/47f00c0f-e90f-47ec-b37a-1caca8b9b993)
- The security department now needs to locate the machines, specifically for the Finance and Sales departments. They will be applying a different update to these systems, unlike the systems used by the Marketing department. This query is being used to identify all employees who work in the Finance or Sales department.

![image](https://github.com/ktwindisch/Investigating-Security-Issues-with-SQL-Filters/assets/56203054/c8df022e-7840-4f25-ac7b-c21461da06f2)
- The security team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. This query is being used to identify all employees who do not work in the Information Technology department.

<h4> Summary:  </h4>

I retrieved the following data:<br/>
<ul>
<li>After-hours login attempts: I retrieved all login attempts that were made outside of normal business hours.</li>
<li>Login attempts on specific dates: I retrieved all login attempts that were made on specific dates that I was interested in.</li>
<li>Login attempts outside of Mexico: I retrieved all login attempts that were made from outside of Mexico.</li>
<li>Employee data from the marketing, finance, and sales departments: I retrieved employee data from these departments for investigation purposes.</li>
<li>Employees who were part of all other remaining departments that were not in the information technology department: I retrieved employee data from all departments that were not in the information technology department.</li></ul>

This data helped me to identify the potential security issues and to take steps to mitigate the risks.<br/>

Here are some of the security issues that I identified:<br/>
<ul>
<li>There were a number of after-hours login attempts. This could be a sign that someone was trying to gain unauthorized access to the system.</li>
<li>There were a number of login attempts on specific dates. This could be a sign that someone was trying to access the system at a time when they knew the system would be less secure.</li>
<li>There were a number of login attempts from outside of Mexico. This could be a sign that someone was trying to access the system from a foreign country.</li>
<li>There were a number of employees in the marketing, finance, and sales departments who had made suspicious login attempts.</li>
<li>There were a number of employees in departments other than the information technology department who had made suspicious login attempts.</li>
</ul>

As a security professional at a large organization, I recently discovered some potential security issues involving login attempts and employee machines. I used SQL filters to retrieve records from different datasets to investigate these issues.
SQL can be used to achieve a better security posture by helping to identify and prevent security threats. By using these queries, businesses can gain valuable insights into their security posture and take steps to mitigate risks.

