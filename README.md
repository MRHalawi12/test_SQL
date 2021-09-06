# test_SQL


jawaban soal https://www.testdome.com/questions/sql/workers/13562?visibility=1&skillId=17:
SELECT name FROM employees
WHERE id NOT IN (SELECT managerId FROM employees WHERE managerId IS NOT NULL);
