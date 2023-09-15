<img width="533" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/c9f4482b-3050-4518-b9f6-6d535a41c57e">


    SELECT ROUND(avg(DAILY_FEE),0) as AVERAGE_FEE
    from CAR_RENTAL_COMPANY_CAR
    where CAR_TYPE like ("SUV")
