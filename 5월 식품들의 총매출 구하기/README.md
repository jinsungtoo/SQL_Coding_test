![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/f4c1f0cf-6e45-4c6d-88c9-34e2946d256d)
![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/fbae7226-615c-4d09-afdb-2d581c069409)



    SELECT A.PRODUCT_ID, A.PRODUCT_NAME, SUM(A.PRICE*AMOUNT) AS TOTAL_SALES
    FROM FOOD_PRODUCT AS A
    JOIN FOOD_ORDER AS B ON A.PRODUCT_ID = B.PRODUCT_ID
    WHERE DATE_FORMAT(PRODUCE_DATE, '%Y-%m') = '2022-05'
    GROUP BY A.PRODUCT_ID
    ORDER BY TOTAL_SALES DESC , A.PRODUCT_ID
