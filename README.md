# MyGitProjectFeb

LIST OF EMPLOYEE FOR IT DEPARTMENT
---------------------------------
SELECT D. DEPARTMENTID, D.DEPARTMENTNAME, E.EMPLOYEENAME FROM DEPARTMENT D
JOIN EMPLOYEE E
ON D.DEPARTMENTID=E.DEPARTMENTID 
WHERE D.DEPARTMENTNAME='IT';
