<img width="543" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/f3c59265-5173-4eae-99ed-b1084f8a3344">


    SELECT MEMBER_ID, MEMBER_NAME, GENDER, 
    DATE_FORMAT(DATE_OF_BIRTH, '%Y-%m-%d') AS DATE_OF_BIRTH
    FROM MEMBER_PROFILE
    WHERE GENDER = 'W' AND MONTH(DATE_OF_BIRTH) = 03 AND TLNO IS NOT NULL
    ORDER BY MEMBER_ID
