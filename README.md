# Excel-Functions-1

# And Function
Check if the Pokemon type is fire and has speed greater than 70

=AND(B2:B10="Fire",C2:C10>70)
 
![image alt]( https://github.com/nsankareswari-70/Excel-Functions-1/blob/b3b63ca8f7b407194ca999c2e1c677fecf9e0a6b/ex1.png)

# If and And function - combination

=IF(AND(B2:B10="Fire",C2:C10>70),"Yes","No")

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/57d62b177012c17594ffe5860019d171a2c9b5e1/ex3.png)

# Average Function
=AVERAGE(B2:E2)
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/46d3b19de6764952bd0d099cc5ccfc8216b329c8/ex4.png)

# Note: The average function ignores cells with text and completes the calculation.

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/34c1a70bad4dea198d053458f2d74edd57eadf20/ex5.png)

# Averageif function

=AVERAGEIF(B2:B10,D4,C2:C10)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/c2bef0ab341e101eeee982d03fbb0fd39250dfe5/ex6.png)

# AVERAGEIFS function
=AVERAGEIFS(C2:C13,B2:B13,F3,D2:D13,G3)
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/6e04defb38dcf2bb18c9c0c4e72c6b07d0264300/ex7.png)

# Concat function   
=CONCAT(B2," ",A2)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/1e49134110ee7d52748dd9713266d566c93f52ef/ex8.png)
# Count function
Works only for cells with numbers
=COUNT(D2:D21)  --> result 20
=COUNT(A2:A21) --> result 0

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/ed1f6322a37d2961bb83ac7bdf9537cd78095ac3/ex9.png)

# CountA function
The COUNTA function counts cells in a range with values both numbers and letters.
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/0b14a4e8aa9113479e0002fd05a9add5a9af624b/ex10.png)

# Countblank function
The COUNTBLANK function is a premade function in Excel, which counts blank cells in a range.
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/4383625d2ea065198a877adfebf9576c28d8f5ab/ex11.png)

# Countif function
The COUNTIF function is a premade function in Excel, which counts cells as specified.    
=COUNTIF(B2:B21,F5)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/6c1cb2a6013038c708c370caf71c54e46c6fadd5/ex12.png)

# IF function (equal to), IF Function (greater than)

=IF(B2:B10="Grass","Yes","No")
=IF(C2:C10>500,"Yes","No")














