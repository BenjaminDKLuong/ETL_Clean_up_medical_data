ETL Data clean up medical records
========================

In this project, I
* imported the data
* combined data from files
* merged tables together
* replace surname and given_name columns with patients_id columns
* extract email and phone number from contact column
* melted auralin and novodra columns 
* created dose_change column from dose_start and dose_end
* plotted reactions deom auralin and novodra

At the end of this project, the insight I gained from analyzing this data is: 
> We see auralin's dose_change mean is -8.32 and novodra's dose_change mean is 0.38.  In Auralin case, we see the mean is a negative number.  It means the dose_start is less than dose_end.  Patients have to take more medicine.  We can say the dose increase, and patients will pay more to get extra doses.  However, the reaction with Auralin is not severe as with Novodra.  In Novodra case, the mean is 0.38.  It means dose_start is greater than dose_end.  The patients take less medicine as they go.  

![alt pic1](https://github.com/BenjaminDKLuong/ETL_Clean_up_medical_data/blob/master/auralin.png)
![alt pic2](https://github.com/BenjaminDKLuong/ETL_Clean_up_medical_data/blob/master/novodra.png)
![alt pic3](https://github.com/BenjaminDKLuong/ETL_Clean_up_medical_data/blob/master/dose_change.png)