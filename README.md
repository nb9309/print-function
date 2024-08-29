# print-function
-> They are 6 syntax in print function

Syntax 1:
        print(val)
           (or)
        print(val1,val2,...,valn)

-> This syntax print value or values.

syntax 2:
        print('string1','string2',.....,'stringn')
                   or
        print('string'+str(val)+'string'+str(val))

-> str(,) give output as syntax error.
-> str(',') => correct

syntax 3:
         print('string', val)  => print('enter value', a)
                        or
         print('string',a,',',b,'string)
                        or
         print('sum of '+str(a)+str(',')+str(b)+' is '+str(c))

-> str(,) give output as syntax error.
-> str(',') => correct

syntax 4:
         print('sum of {},{} is {}'.format(a,b,c))

-> This function prints(a,b,c) using .format()

syntax 5:
        print(f'sum of {a},{b} is {c})

-> This function prints(a,b,c) using f

syntax 6:
        print(Message Cum Value with format Specifiers )
				          OR
		    print(Value Cum Message with format Specifiers )  => print('sum of %d,%0.2f is %0.2f' %(a,b,c))

=>This Syntax display the Values Cum Message format Specifiers.
=>In Python Programming,
		%d is used for Representing  Integer Data
		%f is used for Representing Float Data
		%s is Used for Representing Str Data
=>If we don't have format specifier for any value then we must convert such value into str by using str().

>>>a=10
>>> print("Val of a=%d" %a)-----------------Val of a=10
>>> a=10
>>> b=20
>>> c=a+b
>>> print("Sum of %d and %d=%d" %(a,b,c))---------------Sum of 10 and 20=30
>>> print("Sum(%d,%d)=%d" %(a,b,c))-----------------------Sum(10,20)=30
