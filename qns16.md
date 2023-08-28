SELECT company, MEDIAN(Salary) AS Msalary
FROM Employee
GROUP BY company;
