SELECT customers.custname, COUNT(orders.orderID) AS orderCount
FROM Orders
INNER JOIN customers ON orders.customerID = customers.customerID
GROUP BY customers.custname
ORDER BY orderCount DESC, customers.custname ASC
LIMIT 5;
