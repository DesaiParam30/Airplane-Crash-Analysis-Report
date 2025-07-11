
1	Problem Statement
Aviation safety depends on identifying and mitigating system failures. The dataset, stored in airplain_crash.csv, contains flight records from Boeing 787-8 Dreamliner aircraft, col- lected on December 6, 2025. It includes 20 features, such as Electrical_System_Status, Volt- age_Level, Current_Load, Engine_Performance, Altitude, Airspeed, Weather_Condition, and System_Failure (binary: 0 for no failure, 1 for failure). The goal is to uncover patterns and predictors of system failures to enable proactive maintenance and enhance operational safety.

2	Abstract
This report analyzes Boeing 787-8 Dreamliner flight data to predict system failures, leveraging exploratory data analysis (EDA) and machine learning. EDA identified high current loads and adverse weather as key risk factors. A Random Forest model, selected for its robustness, achieved 92% precision and 89% recall after hyperparameter tuning. These results provide actionable insights for maintenance scheduling and real-time monitoring, advancing aviation safety.

3	Introduction
Ensuring aviation safety is critical, particularly for advanced aircraft like the Boeing 787-8 Dreamliner. This project analyzes a dataset of approximately 10,000 flight records from Decem- ber 6, 2025, stored in airplain_crash.csv. The dataset includes features such as Timestamp, Flight_ID, Electrical_System_Status, Voltage_Level, Current_Load, Last_Maintenance_Date, Pilot_Communication_Score, Weather_Condition, and System_Failure. Our objective is to build a predictive model to identify flights at risk of system failure, enabling timely maintenance and reducing safety risks.
