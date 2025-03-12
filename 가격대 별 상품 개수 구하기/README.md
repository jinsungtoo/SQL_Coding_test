![image](https://github.com/user-attachments/assets/95b3d52c-9d2c-4db4-b9a4-16242fc79073)


    SELECT TRUNCATE(PRICE, -4) AS PRICE_GROUP, COUNT(*) AS PRODUCTS
    FROM PRODUCT
    GROUP BY PRICE_GROUP
    ORDER BY PRICE_GROUP
