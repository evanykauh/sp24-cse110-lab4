1. prints 3 to console since we use var i and is thus callable throughout the whole function
2. prints 150 to console since discountedPrice is a var and can be called outside of the for loop scope
3. prints 150 to console since finalPrice is a var
4. returns the array [50, 100, 150] since discounted is an array that has each final price pushed into it by the for loop.
5. error: reference error since i is a let variable that cannot be called outside the for loop
6. error: reference error since discountedPrice is a let variable that cannot be called outside the for loop
7. 150 since final price is accessible throughout the function
8. returns the array [50, 100, 150] since discounted is an array that has each final price pushed into it by the for loop.
9. error: reference error since i is a let variable that cannot be called outside the for loop
10. prints 3 since the length of the array is three and length is a constant
11. returns the array [50, 100, 150] since discounted is an array that has each final price pushed into it by the for loop.
12. A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
13. A. '32' since 2 maps to the character value '2'
    B. 1 since '3' maps to the integer value 3
    C. 3 since null maps to interger value 0
    D. 3null since null maps to string 'null'
    E. 4 since true maps to the integer value 1
    F. 0 since false maps to the integer value 0 and null maps to the integer value 0
    G. 3undefined since undefined maps to the string version of itself
    I. NaN because the subtraction operation is not defined when one of the operands is undefined.
14. A. true since '2' maps to the integer value 2 and 2>1
    B. false since '2' has a higher lexicographical order than '1'
    C. true since '2' maps to the integer value 2
    D. false since === means strictly equal 2
    E. false since true maps to the integer value 1
    F. true since Boolean(2) maps is the boolean true
15. The == operator performs type coercion and compares values after converting them to a common type, while the === operator compares both value and type without converting them.
17. the array [2,4,6] is returned. The modifyArray function iterates over the input array [1,2,3], applies the doSomething callback to each element (doubling them), and accumulates the results in a new array, ultimately returning [2, 4, 6].
19. 1
    4
    3
    2