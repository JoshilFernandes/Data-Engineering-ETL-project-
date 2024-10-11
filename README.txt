----------------------------------------------------------------------------------

	HELLO! PLEASE READ THIS FILE BEFORE READING THE DOCUMENTATION!! 

----------------------------------------------------------------------------------


--> In the Documentation, please FOLLOW THE STEPS in the section of "2. FLOW OF EXECUTING THE PIPELINE(S)"

--> IT IS VERY IMPORTANT FOR YOU TO GO THE FOLLOWING URL FOR AIRFLOW WEB UI: http://34.32.28.110:8080/

--> Then, you will see 3 DAGs, each DAG and the execution order has mentioned in the Documentation

--> THE DAG WITH NAME: stock_analysis_dag is independent it has no any kind of prerequisite you can try it!

--> THE DAGS WITH NAMES: stock_analysis_to_gcs_dag and load_data_into_bigquery_dag have a specific order:
    THE TRIGGERING ORDER SHOULD BE: 1-) stock_analysis_to_gcs_dag AND THEN 2-) load_data_into_bigquery_dag


---------------THANKS! ENJOY THE PROJECT AND THE VISUALIZATONS IN THE LOOKER STUDIO!----------------------------