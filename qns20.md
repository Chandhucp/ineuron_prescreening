SELECT Books.Title, SUM(Orders.Quantity) AS totalsold
FROM Books
INNER JOIN Orders ON Books.BookID = Orders.BookID
GROUP BY Books.Title
ORDER BY totalsold DESC
LIMIT 3;
