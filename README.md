# A3C for trader
add new A3C for trader;

增加了新的股票调整;

The stock price is a sin+10  9 to 10 ,volume is cos -1 to 1,make sin and cos as state

股票价格是sin+10，成交量是cos，两个参数作为state

action  is  percentage of  stock in  total assets,0 means no stock ,1 means no money;

动作是股票占比0~1，0表示清仓，1表示满仓;

try a3c to adjust the stock

改用a3c来调仓

code of A3C study from EthanMacdonald.a3c copy from [莫烦Python] : https://morvanzhou.github.io/tutorials/

代码主要来至莫烦https://morvanzhou.github.io/tutorials/
