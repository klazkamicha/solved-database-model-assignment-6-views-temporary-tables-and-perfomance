Download Link: https://assignmentchef.com/product/solved-database-model-assignment-6-views-temporary-tables-and-perfomance
<br>
<strong>Views and Temporary tables</strong>

<strong>Problem #1  </strong>

Create View using rearbooks that returns all authors that have volumes in good condition in the database.

To get full credit, the script should delete the view first, make sure your script is idempotent, meaning I can rerun this statement without erroring out many times.

Write select statement that shows your view data.

<strong>Problem #2 </strong>

Write an update statement that changes author_last_first  ‘Barth, John’ into your first and last name using the view you just created

Did this work? Explain why.

If this worked run and submit queries that prove that it worked for view and table




<strong>Problem #3</strong>

Create view that shows author name and number of volumes present in the database per author

To get full credit, the script should delete the view first, make sure your script is idempotent, meaning I can rerun this statement without erroring out many times.




<strong>Problem #4 </strong>

Write an update statement that changes author_last_first  ‘Bronte, Charlotte’ into your first and last name using the view you just created

Did this work? Explain why.

If this worked run and submit queries that prove that it worked for view and table

<strong>Problem #5 </strong>

Create temporary table that has following information

Book_title, publisher_name, average asking price per book.

Write select statement that shows your view data.




<strong>Performance</strong>




<strong>Problem #6  </strong>

Write select statement that finds author ‘Twain, Mark”

Run the query 5 times, get an average on how long the query runs.

In your Submission for this problem

<ol>

 <li>Submit the query for the problem.</li>

 <li>How long it took to run each time to run the procedure.</li>

 <li>How long it was to run the procedure on average.</li>

</ol>




<strong>Problem #7 </strong>

Execute stored procedure call insert_authors(10000); run this procedure 5 times and  get an average on how long that procedure runs

<ol>

 <li>How long it took to run each time.</li>

 <li>How long it was run on average.</li>

</ol>




<strong>Problem #8 </strong>

<strong>Rerun the query from the problem #6 5 times</strong> and write down each time and average.

Figure out what to do to speed up the query.

Rerun the query 5 times again and calculate the average.

<ol>

 <li>How long it took to run query to find Mark Twain records each time after you run procedure in #7.</li>

 <li>How long it was run on average.</li>

 <li><strong>Submit the fix for the performance done.</strong></li>

 <li>How long it took to run each time after the fix.</li>

 <li>How long it was run on average after the fix.</li>

 <li>Describe in few words what you did and what happened, why we see numbers we see.</li>

</ol>




<strong>Problem #9 </strong>

<ol start="3">

 <li>Run call insert_authors(10000) 5 more times after the performance fix</li>

 <li>Write down how long it took to run each time and average to run the procedure.</li>

 <li>Describe in few words what you did and what happened, why we see numbers we see.</li>

</ol>




<strong>Problem #10</strong>

<ol>

 <li>Alter table Publishers to have another column Preferred type bool, default value false.</li>

 <li>Run query that returns publisher Macmillan, and his Preferred status.</li>

 <li>Run the query 5 times and time it, and also calculate the average.</li>

</ol>




<strong>Problem #11 </strong>




<ol>

 <li><strong>Create</strong> stored procedure <strong>insert_publishers</strong>(publisherCount INT) using procedure insert_authors(authorsCount INT) from the script <a href="https://lwtech.instructure.com/courses/2075028/files/169338549?wrap=1">sql</a>  as an example</li>

</ol>




This procedure should insert publisher with random publisher_name (varchar) and random Preferred value (true or false).




<ol start="2">

 <li>Run stored procedure insert_publishers(10000) 5 times and record times and average.</li>

</ol>




<strong>Problem #12 </strong>

<ol>

 <li>How long it takes to run the query to find Macmillan publisher records each time before the performance fix.</li>

 <li>How long it was run on average each time before the performance fix.</li>

 <li><strong>Submit the fix for the performance.</strong></li>

 <li>How long it took to run each time to run the query after the fix.</li>

 <li>How long it was run on average after the fix.</li>

 <li>Describe in few words what you did and what happened, why we see numbers we see.</li>

</ol>