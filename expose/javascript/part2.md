1. "3." On line 12, the console will print the value of the variable i, which is the index of the last element in the prices array. The for loop processes all elements in the prices arrayso  the value of i will be equal to the length of the array, which is 3. 
2. Line 13 will print 150. The functions takes  as input: prices=[100, 200, 300] and discount=0.5. The last element in prices is 300, so during the last iteration of the for loop, the variable discountedPrice is assigned the value 150. The variable is declared with 'var' keyword so line 12 has access so to printit
3. Line 14 will print 150. The functions takes  as input: prices=[100, 200, 300] and discount=0.5. The last element in prices is 300 so on the final iteration of the for loop, finalPrice is assigned the value 150. finalprice is decalred with 'var' keyword so line14 has access to print it
4. The function will return [50. 100, 150]. The function takes as input: prices=[100, 200, 300] and discount=0.5. For each element in prices, the function multiplies it by (1 - discount) = 0.5 (in this case), rounds it, and push it into the discounted array which is returned at the end of the function
5. The code causes an error. The variable i is decalred with the keyword 'let' in the for loop, which means it can only be accessed in the loop block. Since line 12 is outside the loop'ss cope, it has no access to the variable i so it throws an error. 
6. This code causes an error.  The variable discountedPrice is declared  with the 'let' keyword in the for loop, which means it can only be accessed in the loop. Since line 13 is outside the loop, it has no access to the variable discountedPrice so there is an error when it tried to accessit
7. Line 14 will print "150".The function takes as input: prices=[100, 200, 300] and discount=0.5.  This code outputs the last finalPrice value that was calculated in the for loop. The last element in prices is 300, so in the last iteration of the for loop, the variable "finalPrice" is assigned with value 150
8.The function will return [50, 100, 150]. The function takes as input: prices=[100, 200, 300] and discount=0.5. For each element in prices, the function multiplies it by (1 - discount) = 0.5, rounds it, and push it into discounted array which it returns at the end
9. This code causes an error. The variable i is decalred with the keyword let in the for loop, which means it can only be accessed in the loop. Since line 11 is outside the block, it has no access to the variable "i"
10. Line 12 will print 3. The function takes as input: prices=[100, 200, 300] and discount=0.5. There are 3 elements in prices so the length is 3. Tge variable length is declared with const keyword  and assigned the value of the length of prices which is 3. 
11. The function will return [50, 100, 150]. The function returns the value of discounted array. The variable of discounted is declared with keyword const but its elements can be updated\
12. A. student.name  B.student['Grad Year'] C. student.greeting() D. student['Favorite Teacher'].name E. student.courseLoad[0]
13. i. ‘3’ + 2             '32' because the plus operand concantenates them together because oneis a string
14. ii. ‘3’ - 2                 '1' because the minus subtracts 2 from '3' after converting the string '3' to a number
iii. 3 + null               '3' because null is basically 0 in arthimetic operations
iv. ‘3’ + null              '3null' because 3 is a string, the plus sign concatenates 3 and null as strings
v. true + 3                 '4' because true is converted to 1 in numeric context, and 1+3=4
vi. false + null            '0' because false is converted to 0 and null is also 0
vii. '3' + undefined        '3undefined' because the plus operand concantenates because 3 is a string
viii. '3' - undefined       'NaN' because you can't perform sustraction with unfefined
14. ‘2’ > 1               'true' because 2 is converted to a number, whichvalue is greate rthan 1
‘2’ < ‘12’                'false' because string comparison is done character by character. '2' is greater than '1'
2 == ‘2’                  'true' because double equal allows dif type so string 2 is converted to number
2 === ‘2’                 'false' because value and type are not equal
true == 2                 'false' because true is treated as 1, and 1 is not qual to 2
true === Boolean(2)       'true' because Boolean(x) returns true for any non zero number in javascript, and true is equal to true
15. == checks quality but only compares values (they can be different types) but === is more strict and requires value and type to be equal \n
16. f \n
17.The modifyArray function takes an array ([1,2,3]) and a callback (doSomething function) as arguments. Inside modifyArray, a new empty array newArr is created and its for loop iterates through each element of the input array. For each element, the callback function is called with the element as an argument, and the result is pushed into  newArr. The doSomething function takes the input number, multiplies it by 2, and returns it. After iterating through all elements in the input array, the newArr is returned ( [2,4,6]) \n
18. f \n
19. 1 4 3 2
 
