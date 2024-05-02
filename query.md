SELECT * FROM `students` WHERE YEAR(date_of_birth) = 1990;
SELECT * FROM `courses` WHERE cfu > 10;
SELECT * FROM `students` WHERE YEAR(CURDATE()) - YEAR(date_of_birth) > 30;
Expand Requery Edit Explain Profiling Bookmark Database : university Queried time : 11:58:47
SELECT * FROM `courses`WHERE year = 1 AND period = 'I semestre';
SELECT * FROM `exams` WHERE date = '2020-06-20' AND hour > '14:00:00';
SELECT COUNT(*) AS department FROM departments;
SELECT COUNT(*) AS nophone FROM teachers WHERE phone IS NULL;