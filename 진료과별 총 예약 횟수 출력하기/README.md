<img width="529" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/c9764db9-bd0d-4986-9617-3a0ea5aa0673">


    SELECT MCDP_CD AS '진료과코드', count(*) AS '5월예약건수'
    FROM APPOINTMENT
    WHERE EXTRACT(YEAR_MONTH FROM APNT_YMD) = '202205'
    GROUP BY MCDP_CD
    ORDER BY COUNT(*), MCDP_CD
