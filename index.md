# Forecasting Chronic Wasting Disease with a Metapopulation-SIR Informed Graph Neural Network
<table style="border-collapse: collapse;">
  <tr>
    <td style="border: none;"><img src="./pictures/victor.jpeg" width="150" height="170"></td>
    <td style="border: none;"><img src="./pictures/jack2.jpeg" width="150" height="170"></td>
    <td style="border: none;"><img src="./pictures/joseph.jpeg" width="150" height="170"></td>
  </tr>
  <tr>
    <td style="border: none;">Victor Henriksson</td>
    <td style="border: none;">Jack Keller</td>
    <td style="border: none;">Joseph Yoo</td>
  </tr>
  <tr>
    <td style="border: none;">vhenriksson3@gatech.edu</td>
    <td style="border: none;">jkeller44@gatech.edu</td>
    <td style="border: none;">jyoo339@gatech.edu</td>
  </tr>
</table>

**Downloads:** \
[Paper](./docs/CWD_Final_Paper.pdf) \
[Poster](./docs/CWD_Poster.pdf)

[Source Code](./cwd-forecasting.tgz) \
[Datasets](./data.tgz)

## Summary
Chronic Wasting Disease (CWD) is a fatal, prion-based disease that affects deer populations (i.e., cervids) worldwide. As the disease spreads, an important question arises: how will it influence human behavior, particularly the hunting and consumption of cervids -- especially white-tailed deer in the Midwest and Southeast U.S. -- through disease-management policies? We propose a hybrid machine learning-mechanistic model to forecast the spread of CWD in these regions to better understand its potential impact on human behavior. The model consists of a graph neural network (GNN) whose loss function incorporates a Metapopulation-SIR model using the physics-informed neural network (PINNs) framework. This approach captures both the spatial and temporal dynamics of disease transmission while remaining grounded in epidemiological constraints. We find improved accuracy using the proposed model against a classical Metapopulation-SIR ODE model and other neural network methods, which allows for better prediction of high infection count counties.