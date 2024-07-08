![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/496e6daf-a986-400b-ab7d-ab2832c44a98)


    SELECT o.ANIMAL_ID, o.ANIMAL_TYPE, o.NAME
    FROM ANIMAL_OUTS AS o
    JOIN ANIMAL_INS AS i ON o.ANIMAL_ID = i.ANIMAL_ID
    WHERE 1 = 1
    AND i.SEX_UPON_INTAKE LIKE "Intact%" AND O.SEX_UPON_OUTCOME NOT LIKE "Intact%"
