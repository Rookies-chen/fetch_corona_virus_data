- This is a small project to fetch corona_virus data from http://ncov.dxy.cn/ncovh5/view/en_pneumonia, the chinese name of this company is `丁香医生`
- if you need to know more about 丁香医生, please visit their official website https://dxy.com/
- The database structure is defined in the database.sql file, the main code is under com.sage which is init.py
- there is no address name in the history database table, join_to_get_address_name.sql is used to join the tables to get address name, therefore, you can use it to ETL directly
- The FineReport world corona_virus dashboard template is under finereport/dashboard directory