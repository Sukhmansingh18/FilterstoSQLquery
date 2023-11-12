<h1 align='center'>Applying filters to SQL queries</h1> <br />
<p> For this activity, we are using following table formats.
</p> <br />
<img width="684" alt="Screenshot 2023-11-09 at 2 14 19 PM" src="https://github.com/Sukhmansingh18/FilterstoSQLquery/assets/139189335/4799ef20-04af-4da1-a615-f00b37559617"><br />
<h2 align='left'> Project Description</h2><br />
<p font-family: MyCustomMonoFont, monospace>You are a security professional at a large organization. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines.

Your task is to examine the organization’s data in their <b>employees</b> and <b>log_in_attempts</b> tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.</p> <br/>

<h2 align='left' >Retrieve after hours failed login attempts</h2><br />
<p>To investigate this, you need to query the <b>log_in_attempts</b> table and review after hours login activity. Use filters in SQL to create a query that identifies all failed login attempts that occurred after 18:00. (The time of the login attempt is found in the <b>login_time column</b>. The <b>success</b> column contains a value of <b>0</b> when a login attempt failed; you can use either a value of <b>0</b> or <b>FALSE</b> in your query to identify failed login attempts.)
</p><br/>
<img width="717" alt="Screenshot 2023-11-12 at 10 03 07 AM" src="https://github.com/Sukhmansingh18/FilterstoSQLquery/assets/139189335/0c126218-25dc-4b93-96c0-96d1b31bb6ed">
<br/>
<h2>Retrieve login attempts on specific dates</h2>
<p>A suspicious event occurred on 2022-05-09. To investigate this event, you want to review all login attempts which occurred on this day and the day before. Use filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 or 2022-05-08. (The date of the login attempt is found in the <b>login_date</b> column.)</p><br />
<img width="710" alt="Screenshot 2023-11-12 at 10 15 35 AM" src="https://github.com/Sukhmansingh18/FilterstoSQLquery/assets/139189335/88c86533-40f7-45d2-acb2-b1288028ec98"><br />
<h2>Retrieve login attempts outside of Mexico</h2>
<p>There’s been suspicious activity with login attempts, but the team has determined that this activity didn't originate in Mexico. Now, you need to investigate login attempts that occurred outside of Mexico. Use filters in SQL to create a query that identifies all login attempts that occurred outside of Mexico. (When referring to Mexico, the <b>country</b> column contains values of both <b>MEX</b> and <b>MEXICO</b>, and you need to use the LIKE keyword with <b>%</b> to make sure your query reflects this.)</p>
<img width="708" alt="Screenshot 2023-11-12 at 10 38 28 AM" src="https://github.com/Sukhmansingh18/FilterstoSQLquery/assets/139189335/c4b3bb07-ab09-4a3e-9b08-4ea9a78ddde1"><br/>
<h2>Retrieve employees in Marketing</h2><br />
<p>Your team wants to perform security updates on specific employee machines in the Marketing department. You’re responsible for getting information on these employee machines and will need to query the employees table. Use filters in SQL to create a query that identifies all employees in the Marketing department for all offices in the East building.

(The department of the employee is found in the department column, which contains values that include Marketing. The office is found in the office column. Some examples of values in this column are East-170, East-320, and North-434. You’ll need to use the LIKE keyword with % to filter for the East building.)</p><br />
<img width="713" alt="Screenshot 2023-11-12 at 10 49 24 AM" src="https://github.com/Sukhmansingh18/FilterstoSQLquery/assets/139189335/86eba605-bec7-40cd-8b4d-2e8d68c861b4"><br />
<h2>Retrieve all employees not in Information Technology</h2><br />
<p>Your team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. Use filters in SQL to create a query which identifies all employees not in the IT department. (The department of the employee is found in the department column, which contains values that include <b>Information Technology</b>.)</p><br />

<h2>Summary</h2>
<p></p>




