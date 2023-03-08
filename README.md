# 托盘装箱优化问题

1.摆放分布图示

2.各摆放分布平面能放置的最多箱数


A摆放

    n = int(L/l)
    
    m = int(W/w)


B摆放

    n = int(L/w)
    
    m = int(W/l)



C摆放

    max p*q+m*n
    
    s.t.
    
    L >= q*w+m*l
    
    W >= n*w+p*l
    
    m*l >= q*w
    
    p*l >= n*w

