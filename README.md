# Final year project on time series forecasting using LSTM

## Please only run one alternate model at a time and comment out the models not in use. Please make sure to clear previous model when running a new one using from keras import backend as K // K.clear_session().

Time series forecasting to predict future energy consumption using the dataset created by Goncalves et.al on a community’s energy generation and consumption with appliance allocation. The problem the system addresses is individuals and businesses being unaware of their potential future energy usage, the aim is to reduce the impact energy wastage has on the environment and limiting business or individual energy costs. The dataset contains total consumption and PV production profiles split into 15 min intervals over a period of 366 days. The approach to solve the problem used is a recurrent neural network (RNN) type called long short-term memory (LSTM) to perform time series forecasting. The model showed positive performance metrics of the average MSE, RMSE and MAE on the train, validate and test data normalised by the mean, gave values 8.13%, 31.9% and 24.8% respectively. The results show that future energy consumption can thus be accurately predicted and is comparable to other relevant LSTM models and to alternate time series forecasting methods.

Key results:
<img width="432" alt="image" src="https://github.com/user-attachments/assets/3cc59baf-d461-4d06-b821-2f35e13babbd" />
<img width="444" alt="image" src="https://github.com/user-attachments/assets/447d8cff-17ff-4ff3-9c0f-9277f6a7dede" />
<img width="439" alt="image" src="https://github.com/user-attachments/assets/1b4738e4-5581-4a46-809c-7fb52de1fd8e" />
<img width="429" alt="image" src="https://github.com/user-attachments/assets/b5aab91b-ebe8-428e-ad85-1870fdb1e79e" />
<img width="433" alt="image" src="https://github.com/user-attachments/assets/0357089f-7ccf-4cd3-9136-3ce831b48377" />

