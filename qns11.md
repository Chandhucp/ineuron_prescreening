CREATE TABLE Student (
  ID INT NOT NULL PRIMARY KEY,
  Name VARCHAR(20) NOT NULL,
  Age INT NOT NULL,
  Address VARCHAR(25) NOT NULL
);

INSERT INTO Student (ID, Name, Age, Address)
VALUES (1, 'Chandhu', 24, '5th B Cros'),
       (2, 'ganesh', 21, '4th B Street'),
       (3, 'Ajay', 24, 'Laggere'),
       (4, 'Naveedh', 23, 'Jakkur'),
       (5, 'Rajesh', 27, 'chennai');
