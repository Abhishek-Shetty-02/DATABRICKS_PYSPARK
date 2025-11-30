**Scenario: 1**

<pre>
Input:
+------+------+------+
|Team_1|Team_2|Winner|
+------+------+------+
| India|    SL| India|
|    SL|   Aus|   Aus|
|    SA|   Eng|   Eng|
|   Eng|    NZ|    NZ|
|   Aus| India| India|
+------+------+------+
</pre>

<pre>
Expected Output:
+---------+--------------+----------+------------+
|team_name|matches_played|no_of_wins|no_of_losses|
+---------+--------------+----------+------------+
|       SL|             2|         0|           2|
|    India|             2|         2|           0|
|      Eng|             2|         1|           1|
|       SA|             1|         0|           1|
|      Aus|             2|         1|           1|
|       NZ|             1|         1|           0|
+---------+--------------+----------+------------+
</pre>

Scenario 01 Solution:

PySpark - https://github.com/Abhishek-Shetty-02/DATABRICKS_PYSPARK/blob/main/SCENARIOS_01_TO_05.ipynb


...........................................................................................................................

**Scenario: 2**

<pre>
Input:
+-----------+-------------+------------+
|employee_id|department_id|primary_flag|
+-----------+-------------+------------+
|          1|            1|           N|
|          2|            1|           Y|
|          2|            2|           N|
|          3|            3|           N|
|          4|            2|           N|
|          4|            3|           Y|
|          4|            4|           N|
+-----------+-------------+------------+
</pre>

<pre>
Expected Output:
+-----------+-------------+
|employee_id|department_id|
+-----------+-------------+
|          1|            1|
|          2|            1|
|          3|            3|
|          4|            3|
+-----------+-------------+
</pre>
Scenario 02 Solution:

PySpark - https://github.com/Abhishek-Shetty-02/DATABRICKS_PYSPARK/blob/main/SCENARIOS_01_TO_05.ipynb
.....................................................................................................

**Scenario: 3**
<pre>
Input:
+-----------------------+
|customer_name          |
+-----------------------+
|kasireddy naidu        |
|konidela ram charan    |
|Nandamuri tarak ramarao|
|charan                 |
+-----------------------+
</pre>
<pre>
Expected Output:
+---------------------------+----------+-----------+---------+
|customer_name              |First_name|Middle_name|Last_name|
+---------------------------+----------+-----------+---------+
|[kasireddy, naidu]         |Kasireddy |Naidu      |NULL     |
|[konidela, ram, charan]    |Konidela  |Ram        |Charan   |
|[Nandamuri, tarak, ramarao]|Nandamuri |Tarak      |Ramarao  |
|[charan]                   |Charan    |NULL       |NULL     |
+---------------------------+----------+-----------+---------+
</pre>

Scenario 03 Solution:

PySpark - https://github.com/Abhishek-Shetty-02/DATABRICKS_PYSPARK/blob/main/SCENARIOS_01_TO_05.ipynb



.....................................................................................................

**Scenario: 4**
<pre>
Input:
+----+-------+------+----------+
|t_id|user_id|amount|    t_date|
+----+-------+------+----------+
|   1|    101| 500.0|2024-01-01|
|   1|    101| 600.0|2024-01-01|
|   2|    102| 200.0|2024-01-02|
|   3|    101| 300.0|2024-01-03|
|   4|    103| 100.0|2024-01-04|
|   5|    102| 400.0|2024-01-05|
|   6|    103| 600.0|2024-01-06|
|   7|    101| 200.0|2024-01-07|
+----+-------+------+----------+
</pre>

<pre>
Expected Output:
+-------+-----------+
|user_id|total_spent|
+-------+-----------+
|    101|     1600.0|
+-------+-----------+
</pre>

Scenario 04 Solution:

PySpark - https://github.com/Abhishek-Shetty-02/DATABRICKS_PYSPARK/blob/main/SCENARIOS_01_TO_05.ipynb

.....................................................................................................
**Scenario: 5**
<pre>
Input:
+----+
|team|
+----+
| RCB|
| CSK|
|  MI|
|PBKS|
+----+
</pre>

<pre>
Expected Output:
+-----+-----+
|team1|team2|
+-----+-----+
|  CSK|  RCB|
|  CSK|   MI|
|  CSK| PBKS|
|   MI|  RCB|
| PBKS|  RCB|
|   MI| PBKS|
+-----+-----+
</pre>
Scenario 05 Solution:

PySpark - https://github.com/Abhishek-Shetty-02/DATABRICKS_PYSPARK/blob/main/SCENARIOS_01_TO_05.ipynb
