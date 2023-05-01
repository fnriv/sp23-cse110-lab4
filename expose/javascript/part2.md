1. prints "3" (length of array)
2. prints "150"
3. prints "150"
4. returns [ 50, 100, 150 ]
5. prints "3" (length of array)
6. error: discountedPrice 's scope is only within forloop
7. prints "150"
8. returns [ 50, 100, 150 ]
9. prints "3"
10. prints "3"
11. returns [ 50, 100, 150 ] 
12. see below
    1.  student.name
    2.  student[Grad Year]
    3.  student.greeting()
    4.  student[Favorite Teacher].name
    5.  student.courseload[0];
13. see below
    1.  32 - 2 is '2' as a string (String(2))
    2.  1 - '3' is 3 
    3.  3 - null is 0 
    4.  3null - String(null)
    5.  4 - true = 1 
    6.  0 - both false and null convert to 0
    7.  3undefined - String(undefined)
    8.  NaN - '3' converts to 3
14. see below
    1.  true - 2 is converted to Number
    2.  false - unicode: 1 is before 2
    3.  true - 2 is converted to string
    4.  false - true is converted to 1
    5.  true - any number other than 0, -0, and NaN passed into Boolean() passes as true
15.  == performs a loose equality comparison (type changes can happen). === operator, on the other hand, performs a strict equality comparison that does not perform type coercion - the operands to have the same type (as well as the same value).
16. see below
    ```
    for (const prop in obj) {
        if (obj.charAt(0) == 'r') {
            console.log(`obj.${prop} = ${obj[prop]}`);
        } else if (obj % 2 == 1) {
            console.log(`obj.${prop} = ${obj[prop]}`);
        }
    }
    ```
17. output: [ 2, 4, 6 ]. line 4 pauses the function to call doSomething() in order to access the value
18. see below
    ```
    function func18() {
        let d = new Date();
        let time = d.toLocaleTimeString();
        console.log(time);
    }

    setInterval(func18, 1000);
    ```
19. 1 4 3 2