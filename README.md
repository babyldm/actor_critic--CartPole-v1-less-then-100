
# actor_critic--CartPole-v1-less-then-100
add new Stock allocation (try Stock allocation );

增加了新的股票调整;

The stock price is between 9 and 10, assuming it is the sin function as state [0,0,0,0,0,0,0,0,0,0,0,1] to [1,0,0,0,0,0,0,0,0,0,0,0];

股价在9到10块，假定是一个sin波作为状态，编码为[0,0,0,0,0,0,0,0,0,0,0,1] to [1,0,0,0,0,0,0,0,0,0,0,0]；

action  is  percentage of  stock in  total assets [0~10],0 means no stock ,10 means no money;

动作是股票占比，0~10，0表示清仓，10表示满仓;

code of actro_ctritic study from EthanMacdonald.

代码主要来至EthanMacdonald.

