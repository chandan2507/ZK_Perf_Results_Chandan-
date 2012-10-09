ZK_Perf_Results_Chandan-
========================

Measuring Performance of Zookeeper
In this we have taken different cases which are as follows :-

STANDALONE CASES

1) configuration  was using 3.3.6 server and performance was 3000 precisely --- 43-47 sec ---> script_3.3.6.csv

2) configuration was 3.4.4 server 3.4.3 jars  --- - 5000 time  -- 32 seconds ---> script_3.4.4_csv

3)  configuration was 3.4.5 SERVER AND RC0 :--- 4711 almost 5000 and  30-33 sec  --> script_3.4.5_rc0.csv

REPLICATED SERVER CASES

4) no. of vm in ensemble =1 :--- 2144 71-74 seconds    ---> script_3.4.5_replicate_rc0_1server.csv

5) no of vm in ensemble =3  :---  2193   67-68 seconds     ---> script_3.4.5_replicate_rc0_3server.csv


