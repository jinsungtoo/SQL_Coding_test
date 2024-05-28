![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/37098c07-5402-4377-8fe0-f907f52d21b3)


    SELECT i.ANIMAL_ID, i.NAME
    FROM ANIMAL_INS AS i
    LEFT JOIN ANIMAL_OUTS AS o 
    ON i.ANIMAL_ID = o.ANIMAL_ID
    WHERE i.DATETIME > o.DATETIME
    ORDER BY i.DATETIME
