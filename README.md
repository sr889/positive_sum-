# positive_sum-
# Addiert alle positiven Zahlen in einem Array 
def positive_sum(arr):
    result = 0
    for e in arr:
        if e > 0:
            result += e
    return result
