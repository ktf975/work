# work#1.
def my_max(*a):
    max=a[0]
    for i in a:
        if i > max:
            max=i
        else:
            max=max
    return max














#2.
def my_min(*a):
    min=a[0]
    for i in a:
        if i<min:
            min=i
        else:
            min=min
    return min














#  3.
def my_sum(*a):
    add=0
    for i in a:
        add= add+i
    return add

    














# 4.
def my_avg(*b):
    add=0
    for i in b:
        add=add+i
    result = add / len(b)
    return result



