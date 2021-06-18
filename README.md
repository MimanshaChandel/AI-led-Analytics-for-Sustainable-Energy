# AI-led-Analytics-for-Sustainable-Energy

**What's the problem?**

From the beginning of time the human population is dependent on different forms of energy for their functioning. The Industrial Revolution saw the sudden surge in the usage of fossil fuels as the primary source of energy. For years they have been a dominant players in the energy market.
However, fossil fuels (oil, gas, coal) have very adverse impact on the environment mainly due to large amount of Carbon dioxide emissions which are released into the environment when they are burned. CO2 is a main green house gas which traps heat in the atmosphere causing global warming, therefore leading to global climate change.
As per official reports 89% of global CO2 emissions come from fossil fuels. Therefore, the need of the hour is to monitor the consumption of these resources and switch to some safer alternatives such as renewable energy sources (Solar, Wind, Hydropower).

**How can technology help?**

In India due to high population, the vast consumption of the energy has adversely impacted the environment in terms of air pollution which affects the health of the population and also in due course if the consumption is not monitored, we might not be left with enough resources to consume.
Therefore, energy consumption in India could be made more resilient to environment and could move towards green energy using AI led Analytics for Sustainable Energy.

**Idea**

The Idea of the solution is in line with the sustainability goals listed by the UN. It deals with building an intelligent AI led Energy Analytics solution which aims to monitor the Energy consumption and CO2 emissions in high population density areas taking data from smart grids and sensors. It then learns from this data to predict the future energy consumption and CO2 emission for next n years (say 5). In short, it will automatically project the future consumption of the resources and CO2 emissions. It will also help in monitoring the anomalies in the atmospheric gas levels like sudden increase in CO2 so that it could be used by regulatory services or authorities to take proactive measures. 

**Demo Video**

**The architecture**

![image](https://user-images.githubusercontent.com/62833149/122596975-4f548180-d088-11eb-907c-ae7b33e509f2.png)


1. Data received from sensors is send to ibm watson iot.
2. Data collected from ibm watson iot is send to ibm cloud storage
3. Real time data analytics is done on the data.
4. This data is used to train the model for  forecasting predicting and the future values for energy consumption and CO2 emission using Watson Machine learning service of IBM      watson studio.
5.  The historic and predicted analytics on the data is depicted using IBM Cognos Dashboard.
6.  Users acces the IBM Cognos dashboard via exposed endpoint URL.

**Build With**

1.IBM watson Studio
2.IBM Cognos Dashboard
3.IBM Watson Machine Learning Service


**Detailed Description**

The data recieved from sensors is sent to IBM watson IOT. From there the data is loaded to IBM cloud storage. Real Time analytics is done on data to show the current trend of the fossil fuel consumption per capita CO2 emissions from fossil fuels and renewable energy consumption per capita. This data is used to train Time sries ALgorith ARIMA and Regression models(Linear Regression) for predicting future values for next 5 years.
