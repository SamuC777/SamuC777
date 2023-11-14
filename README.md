CREATE TABLE peoples(
    id INTEGER PRIMARY KEY,
    name CHAR(20),
    age CHAR(2)
);

INSERT INTO peoples VALUES (1, 'name 1', '22');
INSERT INTO peoples VALUES (2, 'name 2', '33');
INSERT INTO peoples VALUES (3, 'name 3', '44');
INSERT INTO peoples VALUES (4, 'name 4', '55');

SELECT * FROM peoples
