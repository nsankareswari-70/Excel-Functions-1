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

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/5cda06346c65e70b126604e4953d358563bce869/ex13.png)

# Ifs function

Speed category
&gt;90 Fast
&gt;50 Normal
&lt;=50 Slow

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/8aa56961e71f51c7eef6d734049bee65cc4a3c0f/ex14.png)

# Left function
=LEFT(A2,3)   

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/1091014dee106243c59fea7f511175b9a5f256fe/ex15.png)


# Lower function

=LOWER(A5)
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/f882fc5c2e38f4a5d71f42c3c645913bf38a3dc7/ex16.png)

# Max function

=MAX(D2:D21)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/54df9b978e8a4a47d355eed011bcb753fe0f8cd3/ex17.png)

# Median Function

=MEDIAN(A25:G25)  

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/bc90e46d51c92c2f5244f85897e8d9898a6ef7fe/ex18.png)

# Min Function

=MIN(C5:C24)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/862fd67ff0a457a7a857c16eac02711cecd06428/ex19.png)

# Mode function

Return the number occured many times.
=MODE(B2:E7)
![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/053931941d94cb81754d1017cbbaa9e42bc5762d/ex20.png)

# NPV function

The NPV function is used to calculate the Net Present Value (NPV)

=NPV(B9,B2:K2)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/f39bf79159dacb6ba2d87eb400e6d5518de18230/ex21.png)

# OR function

=OR(B2:B10="Water",C2:C10>60)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/6a1b252669ecd8ab09ae6b772dbe83a9b5d5a718/ex22.png)

# Rand function
The RAND function is used to generate random numbers.
# Right function
To retrieve values from the right side of an Excel cell
=RIGHT(A2,3)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/c5589097d8a50dbf33e8a9f4d28bc303bf64bd05/ex23.png)

# STDEV.S Function
calculates the Standard Deviation (Std) for a sample.

=STDEV.S(E2:E21)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/9e8fe3c6f80210a2e7a7dc04ea3ec145596aa071/ex24.png)

# Sum function
The =SUM function adds both positive and negative numbers.

=SUM(D2:D10)

![image alt](https://github.com/nsankareswari-70/Excel-Functions-1/blob/52532aa646a0cdf122d6a6317ce0600f7c230013/ex25.png)








