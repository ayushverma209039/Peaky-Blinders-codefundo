# Peaky-Blinders-codefundo-

Floods are the most common and widespread of all natural disasters. Flood is one of the most dangerous natural disasters that occur frequently and can affect large community areas. It has become the main threat to people's lives and properties. Because of this reason, accurate flood prediction is very much needed to provide early warning to residents nearby flood locations so that the area can be evacuated as early as possible and the damage to life and property can be minimized.

Currently, hydrological models are used to get the prediction of flood water levels. However, we want to predict the flood with various parameters like weather forecasts, amount of rainfall, temperature and hydreological maps. Such models are difficult to develop since they involve complex system such as the dynamic of flood water level. Flood water level fluctuate in a non-linear way, thus it is very difficult to predict the flood water level.

We know that ANN has the capability of mapping the non-linear relationship, thus this technique is reliable for predicting flood. Another important criterion of ANN is that it allows multiple variables both in the input and output layers. This is very crucial for flood prediction since the river water level at flood location are often functions of many crucial variables such as river water level at several upstream locations. 

Artificial Neural Networks has been successfully applied in time series prediction such as financial time series forecasting, river flow predictions, network traffic prediction, etc. This is because Artificial Neural Network models perform better than standard linear techniques such as Box-Jenkins model when the time series was in noisy and non-linear condition. The NNARX model is one type of ANN that has dynamic structure that is mainly applied to input-output modelling of nonlinear dynamical system such as time series prediction. Neural Network Autoregressive with Exogenous Inputs (NNARX) is implemented to predict long term (multi-step ahead) univariate time series
Both linear (Autoregressive with Exogenous Input and state space) and nonlinear (polynomial and NNARX) models can be applied to predict performance of the network flow from rainfall measurements. Performance improvements also can be seen by applying nonlinear models namely polynomial and NNARX models. NNARX can be implemented to predict long term (multi-step ahead) univariate time series. The NNARX network can be designed to improve its complex time series prediction performance by using its output feedback loop. From the results, it can be inferred that the proposed model always outperforms traditional neural network based predictors such as Elman Neural Network and Time Delay Neural Network (TDNN) models.
Four inputs can be fed to the NNARX model to predict flood water level some hours ahead of time. The input water levels should be normalized between + 1 and -1 before feeding into the model to keep the water level within the same range. Later, the water levels should be denormalized back to obtain the actual predicted flood water level value at the output. The inputs represent three upstream rivers and δy/δk(fourth input) represents difference of water level at flood location due to rainfall. y^ represents predicted water level at flood location.

The current value of model input is represented by u(t) whereas the current value of model output is denoted bY y(t+1), which represents one step ahead output. The dynamic behaviour of the NNARX model is described by Equation (1) where f is a nonlinear function of its arguments. 
                          γ^(t+1)=f(y^(t), …,y^(t−q+1),u(t), …,u(t−q+1))





