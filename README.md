# Bond Portfolio Risk Management

This is the final project for Computer Simulation and Risk Assessment (a course in my graduate stage)
In this project, I led the team to estimate the Value at Risk (VaR) and Expected Shortfall (ES) of a bond portfolio consisted of two Treasury Inflation Protected securities (TIPS)。

steps：
1.	Applied PCA technology to simulate one-day ahead yield curve, based on which calculated the corresponding spot rate 
2.	Forecasted the CPI in the next 5 years using SARIMA method to obtain the adjusted face value of TIPs bonds in each future period
3.	Simulated the VaR and ES of the portfolio one day later with Bootstrap and Monte-Carlo simulation methods    

# 债券组合风险管理 

该项目是计算机仿真和风险评估（研究生阶段的一门课程）的期末项目。
在这个项目中，我带领团队模拟估算一个通货膨胀保值债券组合 (TIPs)（由两只TIPS债券组成）的风险价值度 (VaR) 及期望损失值 (Expected Shortfall)。

具体步骤：
1. 运用主成分分析 (PCA)技术模拟一天之后的收益率曲线，并基于此计算对应的即期利率
2. 利用SARIMA模型预测未来5年的CPI指数，从而得到TIPs债券未来每期的调整后的票面值
3. 运用Bootstrap以及Monte-Carlo 模拟的方法模拟一天后债券的VaR以及ES

