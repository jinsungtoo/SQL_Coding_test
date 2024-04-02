![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/694c29a1-c9ac-491a-a618-0cfca67362ef)


    SELECT ANIMAL_ID, NAME, CASE WHEN (SEX_UPON_INTAKE LIKE '%Neutered%') THEN 'O'
                        WHEN (SEX_UPON_INTAKE LIKE '%Spayed%') THEN 'O'
                        ELSE 'X' END AS '중성화'
    FROM ANIMAL_INS
    ORDER BY ANIMAL_ID
