# 1. List all distinct job in Employee.
SELECT DISTINCT JOB FROM EMPLOYEE;

# 2. List all information about employee in Department Number 30.
SELECT * FROM EMPLOYEE WHERE DEPTNO = 30;

# 3. Find all department names with department number greater than 20.
SELECT DNAME, DEPTNO FROM DEPARTMENT WHERE DEPTNO > 20;

# 4. Find all information about all the managers as well as the clerks in department 30.
SELECT * FROM EMPLOYEE WHERE DEPTNO = 30 AND JOB IN('MANAGER', 'CLERK');

# 5. List the Employee name, Employee numbers and department of all clerks.
SELECT ENAME, EMPNO, DEPTNO, JOB FROM EMPLOYEE WHERE JOB = 'CLERK';

# 6. Find all managers not in department 30.
SELECT * FROM EMPLOYEE WHERE JOB = 'MANAGER' AND DEPTNO != 30; 

# 7. List information about all Employees in department 10 who are not manager or clerks.
SELECT * FROM EMPLOYEE WHERE DEPTNO = 10 AND JOB NOT IN('MANAGER', 'CLERK');

# 8. Find Employees and jobs earning between 1200 and 1400.
SELECT ENAME, JOB, SAL FROM EMPLOYEE WHERE SAL BETWEEN 1200 AND 1400;

# 9. List Name and Department Number of employee who are clerks, analyst or salesman.
SELECT ENAME, DEPTNO, JOB FROM EMPLOYEE WHERE JOB IN ('CLERK', 'ANALYST' ,'SALEMAN');

# 10. List Name and Department Number of employee whose names began with M.
SELECT ENAME ,DEPTNO FROM EMPLOYEE WHERE ENAME LIKE 'M%';
