# Electrocardiography Signal Processing Project With MATLAB & LTSpice
   The **ecg_data.dat** file contains an actual ECG data representing a real ECG signal
   ![Original ECG Signal](original_ecg_signal.png)

   ## Adding Noise to the ECG Signal
   It was requested to add three different noise to the orijinal ECG signal
   - **Random noise at 50 Hz (simulating power line interference)**
   - **Random low-frequency noise below 0.05 Hz (simulating baseline wander)**
   - **Random high-frequency noise above 150 Hz (simulating muscle artifacts and other high-frequency disturbances)**

   The **ecg_data_noisy.txt** file is a data file that stores the noisy ECG signal
   ![Noisy ECG Signal](noisy_ecg_signal.png)

   ## Filtering the Noisy ECG Signal
   A filter circuit was designed and simulated in LTSpice to remove the introduced noise components. The **filter.asc** file is simulation file that contains a filter circuit
   ![Filter Circuit](filter_circuit.png)

   The **filter.txt** file is a data file that stores the filtered ECG signal
   ![Filtered ECG Signal](filtered_ecg_signal.png)