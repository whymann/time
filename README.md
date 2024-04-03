# time
choice = input("do you want the distance in miles or kilometers")
if choice == 'm':
    distance = float(input("How many miles would like to travel?"))
elif choice == 'k':
    distance = float(input("How many Kilometers would you like to travel?"))


#print out conversion
if choice == 'm' or choice == 'M':
    print("Converted to km:", distance*1.6)
#our part
if choice == 'k' or choice == 'K':
    print("Converted to miles:", distance*0.6)
    
    

#time = distance/speed
if choice == 'm' or choice == 'M':
   time = distance/15
   print(time*60)
   
#you need to find the time when you're given km. speed = distance ÷ time
if choice == 'k' or choice == 'K':
   time = distance/15
   print(time*60)




   
A = 1+.15*time
if time<=5:
    B = 2.5*time
else:
    B - 2.5*5 + .12*time 
C = 5+.06*time

if A<B and A<C:
    print("use company A")
elif B<A and A<C:
    print("use company B")
#need one more here
elif C<A and C<B:
    print("use company C")
