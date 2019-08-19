#GCD using recursion
m=int(input("Enter Value 1"))
n=int(input("Enter Value 2"))

def gcd(m,n):
    if(n==0):
        return m
    else:
        return gcd(m,n%m)

print ("The GCD of the 2 numbers are " )
print(gcd(m,n))
