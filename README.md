        --  sqlcoding-project---1

SQL Code Challenge
1. Create Database, Tables and Relations.
Using the CSV files located in source_data/csv_data, create your new SQL database and tables with the properly formatted data.

Add a numeric, auto-incrementing Primary Key to every table.
In the countries table, add the column created_on with the current date.
Create a one-to-one and one-to-many relationship with the countries table as the parent table.
2. List Regions and Country Count
List all of the regions and the total number of countries in each region. Order by country count in descending order and capitalize the region name.

Click to expand expected results!
Click to expand answer!

3. List Sub-Regions and City Count
List all of the sub-regions and the total number of cities in each sub-region. Order by sub-region name alphabetically.

Click to expand expected results!
Click to expand answer!

4. Specific Sub-Region and String Functions
List all of the countries and the total number of cities in the Northern Europe sub-region. List the country names in uppercase and order the list by the length of the country name and alphabetically in ascending order.

Click to expand expected results!
Click to expand answer!

5. List Specific Countries by Year
List all of the countries and the total number of cities in the Southern Europe sub-region that were inserted in 2021. Capitalize the country names and order alphabetically by the LAST letter of the country name and the number of cities.

Click to expand expected results!
Click to expand answer!

6. List Anti-Join
List all of the countries in the region of Asia that did NOT have a city with an inserted date from June 2021 through Sept 2021.

Click to expand expected results!
Click to expand answer!

7. Reversable Names
List the country, city name, population and city name length for the city names that are palindromes in the Western Asia sub-region. Format the population with a thousands separator (1,000) and format the length of the city name in roman numerals. Order by the length of the city name in descending order and alphabetically in ascending order.

Click to expand expected results!
Click to expand answer!

8. Search with Wildcard and Case
List all of the countries that end in 'stan'. Make your query case-insensitive and list whether the total population of the cities listed is an odd or even number for cities inserted in 2022. Order by whether the population value is odd or even in ascending order and country name in alphabetical order.

Click to expand expected results!
Click to expand answer!

9. Ranking Regions
List the third most populated city ranked by region WITHOUT using limit or offset. List the region name, city name, population and order the results by region.

Click to expand expected results!
Click to expand answer!

10. Using Buckets
List the bottom third of all countries in the Western Asia sub-region that speak Arabic. Include the row number and country name. Order by row number.

Click to expand expected results!
Click to expand answer!

11. Using Arrays
Create a query that lists country name, capital name, population, languages spoken and currency name for countries in the Northen Africa sub-region. There can be multiple currency names and languages spoken per country. Add multiple values for the same field into an array.

Click to expand expected results!
Click to expand answer!

12. Using Case and Percentages
Produce a query that returns the city names for cities in the U.S. that were inserted on April, 28th 2022. List how many vowels and consonants are present in the city name and concatnate their percentage to the their respective count in parenthesis.

Click to expand expected results!
Click to expand answer!
 
 13. Most Consecutive Days
List the most consecutive inserted dates and the capitalized city names for cities in Canada that where inserted in April 2022.

 Click to expand expected results!
Click to expand answer!

  14. Month over Month in View
Create a view that lists the month-year, the number of cities inserted for that month, a running city count total and the month over month percentage growth for 2021.

Format the cities count and the running total with the thousands separator and format the month over month growth with a plus symbol and percentage symbol

Example:
 
month_year	cities_inserted	running_total	month_over_month
Feb-2021	1,291	2,762	+87.76%


 
 15. Stored Procedure to CSV
Create and call a stored procedure that lists a unique row id number, insert date, country name, city name, population and languages spoken for countries in the Latin America and Caribbean sub-region that were inserted on either '2022-04-09', '2022-04-28' or '2022-08-11'.

Order by the insert date and output the results (including headers) to a CSV file located in /source_data/csv_output/ .
--------------------------------------------------------------------------
