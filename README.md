# string-concepts
5. >>> string ='sridharrouthu23'
   >>> string[:10:1]
   'sridharrou'
6. >>> string ='sridharrouthu23'
   >>> string[-10::]
   'arrouthu23'
7. >>> string= 'abcdabcd'
   >>> print(string.count("a"))
   2
8. >>> var='abcdabcd'
   >>> var.find('a')
   0
9. >>> var='abcdabcd'
   >>> var.rfind('a')
   4
10.>>> var='abcdef'
   >>> var1=" ".join(var)
   >>> print(var1)
   a b c d e f
11.>>> var=input("input string
   is ")
   input string is assam
   >>> var1=input("input character     is ")
   input character is a
   >>> print("if character is    present then it is true    otherwise it is false")
   if character is present then it    is true otherwise it is false
   >>> 'a' in var[0]
   True
   >>> 'a' in var[-1]
   False
12.>>> var=input("input string
   is ")
   input string is assam
   >>> var4=var.center(20)
   >>> print(var4)
   '       assam        '
13.>>>string='i like travelling.'
   >>>string.title()
   'I Like Travelling.'
14.>>> string= '     hello     '
   >>> print(string.strip())
   hello
15.>>> var="sridhar"
   >>> var.upper()
   'SRIDHAR'
16.>>> var="SRIDHAR"
   >>> var.lower()
   'sridhar'
17.>>> var="abcdefgh"
   >>> var1="abc"
   >>> var2="xyz"
   >>> print(var.replace(var1,var2))
   xyzdefgh
18.>>> while True:
        x=input("enter input ")
         if x.isalpha() == True:
           continue
         else:
           break

    enter input sri
    enter input dri
    enter input 23 

     var=input("enter input ")

     enter input 10
   >>>var4=x.rjust(10)
   >>>print(var4)
           23













