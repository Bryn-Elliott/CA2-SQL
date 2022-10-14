Rhys' Branch

CA2 SQL Assessment
Group i

Members:
Ella Thomson
Theo Musa
Jonathan Love
Rhys Speers
Bryn Elliott

SELECT invoiceId, customerId, Total - (SELECT AVG(Total) FROM 'invoices') AS priceDiff FROM 'invoices' WHERE Total > (SELECT AVG(Total) FROM 'invoices') AND Total - (SELECT AVG(Total) FROM 'invoices') > 15
