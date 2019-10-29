SQL Basic Order of query:

`SELECT .... FROM .... WHERE ... GROUP BY`

1 - FROM
2 - WHERE
3 - SELECT
4 - GROUP BY / ORDER etc

e.g

Patient Table

patient_id |    name    | doctor
-------------------------------------
0          |    Katie   | 0
1          |    Piet    | 0
2          |    Alice   | 1
3          |    Pipi    | 2

Doctor Table

doctor_id | name
-----------------
0         | Bess
1         | Margot
2         | Julia
3         | Bulbasaur

SELECT name FROM patient GROUP BY doctor HAVING count(*) > 1;

returns:

name  | doctor
--------------
Katie | 0
Piet  | 0