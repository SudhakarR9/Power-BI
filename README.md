# Power-BI
SELECT * FROM people;
use sql15;
SELECT * FROM states;
SELECT * 
FROM people
JOIN states
ON people.state=states.state_abbrev
WHERE people.first_name LIKE "J%" AND states.region= "South";
