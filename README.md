
𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐀𝐢𝐦:

To detect anomalous behavior in battery capacities using different Neural Network models.


𝐖𝐨𝐫𝐤𝐢𝐧𝐠:

We used two datasets, a Training Set and a Testing Set, each containing data from 6 batteries over 495 and 499 cycles, respectively. We had to normalized both dataset. Then, we build our model. First, it was 𝐋𝐒𝐓𝐌 𝐀𝐮𝐭𝐨𝐞𝐧𝐜𝐨𝐝𝐞𝐫 (𝐑𝐍𝐍). Then we trained the model with Training set and observed the output with Testing set. We used two more models - 𝐁𝐢-𝐋𝐒𝐓𝐌 & 𝐆𝐑𝐔. All the above models were based on Reconstruction Error. Finally, we used 𝐋𝐒𝐓𝐌 𝐅𝐨𝐫𝐞𝐜𝐚𝐬𝐭𝐢𝐧𝐠 model which was based on Prediction Error. 
Since, all of the models were correctly detecting the anomalies batteries.
To find efficiency, we found the total number of anomalies in the batteries using each model. 


𝐑𝐞𝐬𝐮𝐥𝐭:

Out of the 6 batteries in the testing set, 4 exhibited anomalous behavior. Remarkably, all four models accurately identified these anomalies.
While calculating the total number of anomalies in batteries, 𝐋𝐒𝐓𝐌 𝐅𝐨𝐫𝐞𝐜𝐚𝐬𝐭𝐢𝐧𝐠 model turned out to be the most efficient one as it detected the highest number of anomalies.

𝐎𝐮𝐭𝐩𝐮𝐭𝐬:

#Detecting Anomalous Batteries in the dataset:

![Forecasting](https://github.com/user-attachments/assets/c934b0f8-ce4b-4d12-956c-a5118b3b01b9)

#Detecting number of anomalies in dataset:

![2](https://github.com/user-attachments/assets/3f76f8e5-f921-4590-97c9-bbe28b327384)

Threshold = 0.013470607995986936

Number of anomalies = 2180
