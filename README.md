# SQL HANDBOOK PREP

- Includes quick revision on SQL queries for backend dev interviews.

# Tricks
``` sql
-- When you have a table say 
-- name  department  laptops
-- Sayanth EEE           2
-- Sunil   ECE           3
-- Sonu    CSE           4
-- Suman   ECE           2

-- If you want to find each dept and total laptops given
-- follow this

select department, sum(laptops) 
from data_info
group by department;

-- group by is where you might have some confusion so focus there. Remember the (DC - GD) pro tip lol!
```