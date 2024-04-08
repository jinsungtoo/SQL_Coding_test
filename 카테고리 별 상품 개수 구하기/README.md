![image](https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/8ecb3675-2fe8-4a51-9756-71db74189bea)


    SELECT SUBSTR(PRODUCT_CODE,1,2) AS CATEGORY, count(PRODUCT_ID) AS PRODUCTS
    from PRODUCT
    GROUP BY CATEGORY
    ORDER BY CATEGORY
