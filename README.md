# Impact of Rainfall on Communication Equipment in Power Distribution

This repository contains research and analysis focused on understanding the influence of atmospheric conditions, particularly rainfall, on the reliability of communication technologies used in electrical power distribution networks. The project emphasizes the resilience of devices like circuit breakers and reclosers, which are integral to the power grid's integrity.

## Overview

Electrical power distribution relies heavily on remotely operated protection and switching equipment. The effective functioning of these systems is paramount to the stability and efficiency of the power grid. This project investigates how environmental factors, especially rainfall, affect the communication technologies (such as fiber optics, GPRS, and KU-Band satellite connections) that underpin these systems.

## Contents

- `rainfall_satellite_availability.ipynb`: A Jupyter Notebook containing detailed data analysis and visualizations.
- `Data/`: Directory containing datasets used in the analysis, including historical weather patterns and equipment performance data.
- `Images/`: Directory containing images used in the Jupyter Notebook.

## Nature of Telecommunications in Power Distribution

A diverse array of communication technologies underpins these systems. These include, but are not limited to, fiber optics, GPRS, and satellite connections (notably the KU-Band). Each of these technologies has its unique attributes and vulnerabilities. For instance, fiber optics offer high bandwidth and low latency but can be costly and challenging to deploy in remote areas. On the other hand, GPRS (General Packet Radio Service) provides wide area coverage but may suffer from lower data rates. Satellite communication, especially in the higher frequency KU-Band, offers extensive coverage but is notably susceptible to atmospheric conditions, such as heavy rain, which can attenuate or disrupt the signal - a phenomenon known as rain fade.

## The Challenge of Atmospheric Phenomena

Atmospheric conditions, particularly precipitation, can significantly impact the reliability of these communication technologies. High-frequency satellite communications, such as those in the KU-Band, are particularly sensitive to such phenomena. Rainfall can cause signal attenuation, leading to potential lapses in the operation and monitoring capabilities of the power distribution network.

## Research Objective

Our primary aim is to investigate the following:
- Establish whether there is a discernible increase in equipment unavailability correlated with higher rainfall indexes, specifically for those technologies vulnerable to atmospheric disturbances.
- Should a correlation be evident, it becomes imperative for maintenance and operational engineers to devise and implement preemptive strategies. This is crucial to maintain uninterrupted power distribution and high-quality service. Utilizing predictive analytics, such as weather forecast data, can be instrumental in anticipating and mitigating communication failures. By integrating meteorological data with network performance metrics, we can develop more resilient and adaptive power distribution systems.

## Leveraging Data and Predictive Analytics

The integration of weather forecasting and telecommunication data presents a promising avenue for enhancing the resilience of power distribution networks. By analyzing historical weather patterns and equipment performance data, we can develop predictive models that anticipate communication disruptions. This proactive approach enables maintenance teams to implement contingency plans effectively, thereby minimizing the impact of adverse weather conditions on the power grid's operational integrity.

This investigation is critical for enhancing the robustness of our power distribution infrastructure and ensuring consistent, high-quality electrical service in the face of environmental challenges.

## Results
The correlation between equipment unavailability and rainfall was found to be negligible for GPRS and satellite communications, with correlation coefficients of -0.006929 and -0.002116 respectively. This suggests that, while rainfall does have an effect on signal quality, other factors may play a more significant role in the overall unavailability of communication equipment. When examining the percentage of unavailability, GPRS showed a higher tendency towards service disruption, with a higher average unavailability rate, compared to satellite communications. These insights direct focus towards improving the robustness of GPRS technology against environmental factors.

## Time Series Analysis
![](images/moving_average.png)
The time series analysis, depicted in the provided charts, illustrates the 30-day moving average of unavailability rates and precipitation for GPRS and satellite technologies. A notable change was observed post the implementation of the "New Maintenance Strategy Rollout" in September. The charts reflect the effectiveness of this strategic change, providing a visual representation of how maintenance practices influence the resilience of communication networks amidst varying weather conditions.

By harnessing the power of data analytics, we can derive actionable insights that propel us towards a future where our power distribution systems are not only smart but also robust against the unpredictability of nature.