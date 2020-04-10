This code will try to understand the COVID19 disease case distribution using the Logistic Growth model both for Germany and Bangladesh. 

Logistic growth is defined by the differential equation-- 
df(t)/dt==k f(t) (1-f(t)/L)

Here k is a continuous growth rate and L is the limit to growth such that f(t) cannot exceed L. When f(t) is small relative to L, (1-f(t)/L) is near 1. Then the initial growth is proportional to f(t) with exponential growth rate, k. When f(t) reaches L growth rate is zero and growth stops. If we require that L and k be positive, then the growth rate is always positive.

​The model was originally developed to account for population growth, with the idea that there was a maximum population, L, that a space could support, and population could not grow beyond that maximum in the space. 

This code was written using Wolfram Mathematica 12.1.0

This code is an amateurish approach to understand the Novel Coronavirus case distribution using Logistic Growth model. This code will give the most updated estimate as the data is being pulled in real time from the John Hopkins University CSSE Novel Coronavirus Database.

Data Source- 
1. https://systems.jhu.edu/research/public-health/ncov/
2. https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6
3. https://github.com/CSSEGISandData/COVID-19
4. Wolfram Knowledge Base for COVID19

Acknowledgement-- 
I took a lot of help from Google, Wolfram Community, Mathematica Stack Exchange forum while preparing this file. Specially the posts and comments of the following authors helped me a lot to navigate the right direction and understand the functions and underlying processes to a great extent-- Andy Ross, Thies Heidecke, James Ferrell, Vitaliy Kaurov, Robert Nachbar,  Chip Hurst, Francisco Rodríguez, Diego Zviovich, Anton Antonov, Robert Rimmer, Mads Bahrami

Thanks to my partner in crime Jahid Jaman (xamanxahid@gmail.com) for providing me with the necessary computing resources.  


 