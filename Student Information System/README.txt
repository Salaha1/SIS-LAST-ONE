This Project is A Student Information System, It is Used By The Student Of Antonine University. Here's Some Option That Can Be Done:

1- After Creating An Account Or Signing in To An Existing One, User Should Choose Between Signing In As Student Or Admin,
If He Choose to Sign in As An Admin A Password "admin" is Required To Proceed, Or If He Choose to Sign IN As Student He Will Proceed
Immediatly.
2-In Case Of Student: There Are 4 Options That Can be Chosen As Student:
*Add Course(Enroll): This Option will Display The Courses Available In Courses excel File So That The User Can Should One Of Them 
To Enroll, Once He Choose A ClassNumber, Validation will be Done To Insure That The Student Can Enroll This Course And When Everything
is Correct The User Will be Registered in This Course, His Student Id will be Written In Front Of The Class Number of the course he
Chose in RegisteredCourse excel File, Capacity of the course will decrease by 1.
*Drop Course: This Option Will Display The Courses That The User Is Already Enrolled In, The User Should Choose a Class Number of 
the enrolled Courses, If Validation Is True, Student Id will be Removed in RegisteredCourse excel File in Front of The class number
chosen and capacity of the Course Will increase by one.
*Swap Course: This Option Will Display Enrolled Courses and let user choose one of them, and then display available courses and
let user choose one of them, if validations are true, It will Drop The First course the user has chosen and increase it's capacity
Then it will enroll the second and decrease it's capacity.
*Schedule: This Option will Display The Courses That The User Enrolled With The Day, StartTime and EndTime of The course.

3-In Case Of Admin: There Are 3 Options That Can Be Chosen As Admin:
*Add Course(Create): This Option Will Add A New Course To Courses excel File. When Creating a new Course There Are Some Things 
That needs to be taken into consideration:

1. FirstName and LastName Should be String Only.

2.Password Should contain At least 1 Upper-case and 1 lower-case Character,Numbers,Symbols, and should be at least 8 Characters.

3.Email Address Should Be in This Format: StudentID@ua.edu.lb ( Replacing StudentID with the auto-generated ID)

4.Phone Number Should Be in This Format: Area Code: YY , Numbers: XXXXXX ,Phone Number: YYXXXXXX (It Shouldn't be Seperated by Space)

*Remove Course: This Option will Display Available Courses in Courses excel file and let user choose one of them to remove it

*Modify Course: This Option Will Display Available Courses in Courses excel file and let user choose one of them to modify, 
Once modifications are done the Data will be Modified In Courses excel file.

4-PDF Should Display The Student Information from students excel file and All the courses the student is enrolled in
sorted in ascending order.






