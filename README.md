c = 0
p = 1.0
count = int(input("Enter the number of values:"))
while(c<count):
    x = float(input("Enter a real number:"))
    c = c+1
    p = p*x
    gm = pow(p,1.0/count)
    print("The geometric mean is:",gm)

Output

Enter the number of values:5
Enter a real number:3
The geometric mean is: 1.2457309396155174
Enter a real number:3
The geometric mean is: 1.5518455739153598
Enter a real number:6
The geometric mean is: 2.22064303492292
Enter a real number:9
The geometric mean is: 3.446095064991105
Enter a real number:0
The geometric mean is: 0.0

