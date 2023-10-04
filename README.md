#program to find first n natural numbers
#requrements are 
#n be passe as an argument
#cal first n natural numbers
#display the sum

#code
def sumsquares(n):
    sum=0
    for i in range(1,n+1):
        sum=sum+i
    print("the sum of first",n ,"natural numbers is",sum)
    #function ends here
#ask number of to be foun natural numbers
num=int(input("enetr the value for n :"))
sumsquares(num)
