Hospital
 - patients table --> date of death (dod)
 - prescriptions table --> 
 - admissions table --> admission type
 - omr table --> result_name, results value (bp, weight)

DB Schema
https://mimic.mit.edu/docs/iv/modules 

## potential research question
 - Among ICU patients with ECG recordings, which ECG features are most predictive of in-hospital mortality?

 - outcome:
    - mortality (hospital expire flag)
 - predictors:
    - reports from ecg table
    - demographic variables (table?)
    - ecg features from ecg table

### report_0
   - Current buckets
      - normal_sinus [x]
      - sinus_tachy [x]
      - sinus_brady [x]
      - afib [x]
      - afib_rvr [x]
      - pvc [x]
      - pac [x]
      - afib_avr [x]
      - paced [x]
      - stemi_alert [x]
   - To make
      - low degree block
      - high degree block
      - atrial_arrhythmia