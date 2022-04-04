


# High Level test plan

|Test ID	|Description	|Exp i/P	|Exp O/P|	Actual O/P|
|------  |   ------  |    ------- |  ----- |   ---|
|H_01|	Electricity bill calculation at urban areas	|Choice	|SUCCESS|	SUCCESS|
|H_02|	Electricity bill calculation at rural areas	|Choice	|SUCCESS|	SUCCESS|
|H_03|	Units consumed per year	|Choice	|SUCCESS|	SUCCESS|
|H_04|	Calculates total industrial loads	|Choice	|SUCCESS|	SUCCESS|



# Low Level test plan

|Test ID|	HL_ID|	Description|	Exp input|	Exp Output|	Actual Output|
|------ |------|---------| --------|-------|------|
|L_01|	H_01|	Electricity bill calculation at Urban areas if(units<30)	|22 units	|71.5 rupees|	71.5 rupees|
|L_02|	H_01	|Electricity bill calculation at Urban areas if(units>30 && units <100)|	50|	235|	235|
|L_03|	H_01|	Electricity bill calculation at Urban areas if(units>101 && units <200)	|150|937.5|	937.5|
|L_04| H_01	|Electricity bill calculation at Urban areas if(units<200)	|230	|1,679	|1,679|
|L_05| H_02	|Electricity bill calculation at Urban areas if(units<30)	|12	|37.8 |37.8|
