![image](https://github.com/user-attachments/assets/af01a2c1-ffcb-4c52-bc77-812fa2385ee0)


    SELECT NAME, COUNT(*) AS COUNT
    FROM ANIMAL_INS
    WHERE NAME IS NOT NULL
    GROUP BY NAME
    HAVING COUNT(*) >= 2
    ORDER BY NAME ASC
