SELECT Person.Name, Address.Addressid, Address.City, Address.State
FROM Person
INNER JOIN Address ON Person.AddressId = Address.AddressId;
