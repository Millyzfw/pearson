import math
def pearson(X,Y):
    n=0
    sum_XY=0
    sum_X=0
    sum_Y=0
    sum_X2=0
    sum_Y2=0
    for key in X:
        if key in Y:
            n+=1
            sum_XY+=X[key]*Y[key]
            sum_X+=X[key]
            sum_Y+=Y[key]
            sum_X2+=X[key]**2
            sum_Y2+=Y[key]**2
    numerator=sum_XY-(sum_X*sum_Y)/n
    denominator=math.sqrt(sum_X2-sum_X**2/n)*math.sqrt(sum_Y2-sum_Y**2/n)
    if denominator==0:
        return 0
    else:
        return (numerator/denominator)
