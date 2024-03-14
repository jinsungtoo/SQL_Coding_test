<img width="637" alt="image" src="https://github.com/jinsungtoo/SQL_Coding_test/assets/115756142/abe4d870-619f-485e-a56e-78ef4ddd3098">


    SELECT BOARD_ID,WRITER_ID,TITLE,PRICE,
      CASE WHEN STATUS = 'SALE' THEN '판매중'
        WHEN STATUS = 'RESERVED' THEN '예약중'
        WHEN STATUS = 'DONE' THEN'거래완료'
        ELSE 0 END STATUS
    FROM USED_GOODS_BOARD
    WHERE CREATED_DATE = '2022-10-05'
    ORDER BY BOARD_ID DESC
