<img width="542" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/a918c0fd-b522-4a7f-93a4-e57eba39a077">


    SELECT DR_NAME, DR_ID, MCDP_CD, DATE_FORMAT(HIRE_YMD, '%Y-%m-%d') AS HIRE_YMD
    FROM DOCTOR
    WHERE MCDP_CD = 'CS' OR MCDP_CD = 'GS'
    ORDER BY HIRE_YMD DESC, DR_NAME;
