<img width="616" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/aeab7bde-f003-4da7-a2e8-af27af26b763">


    SELECT USER_ID, PRODUCT_ID
    FROM ONLINE_SALE
    GROUP BY 1, 2
    HAVING COUNT(PRODUCT_ID) >= 2
    ORDER BY 1,2 DESC
