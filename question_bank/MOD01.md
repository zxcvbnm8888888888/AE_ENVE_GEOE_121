# Module 01: Basic MATLAB Programming

## Table of Contents
- [**M01001. Built-In Functions (★)**](#m01001-builtin-functions)
- [**M01002. Operator Precedence (★★)**](#m01002-operator-precedence)
- [**M01003. Triangle Problem (★)**](#m01003-triangle-problem)
- [**M01004. Swap Three Numbers (★★)**](#m01004-swap-three-numbers)
- [**M01005. Arithmetic Operations (★)**](#m01005-arithmetic-operations)
- [**M01006. Rounding Function (★★)**](#m01006-rounding-function)
- [**M01007. Swap Numbers**](#m01007-swap-numbers)
- [**M01008. Arithmetic Operation (★)**](#m01008-operator-precedence)
- [**M01009. rem Function**](#m01009-rem-function)
- [**M01010. Type Casting and rem Function (★★)**](#m01010-type-casting-and-rem-function)

## M01001. Built-In Functions (★) 

```matlab
% https://www.mathworks.com/help/matlab/ref/rand.html
r1 = 12*(rand(1)*2-1); % a random real number between -12 and 12
r2 = 12*(rand(1)*2-1); % a random real number between -12 and 12
```

You need to write a script that creates a variable named:
(a) 's_a' which is copied from 'r1'. Please round-off the value in 's_a' towards nearest integer. 
(b) 's_b' which is copied from 'r1'. Please round-off the value in 's_b' towards negative infinity. 
(c) 's_c' which is copied from 'r2'. Please round-off the value in 's_c' towards positive infinity. 
(d) 'l_d'. If the 'r1' is larger than 'r2', assign 'true' to 'l_d'. Otherwise, assign 'false'. 
(e) 'l_e'. If the absolute value of 'r1' is larger than the absolute value of 'r2', assign 'true' to 'l_d'. Otherwise, assign 'false'. 

**Solution**
Please watch this:[**https://youtu.be/nYWJNN0uQCg?t=21**](https://youtu.be/nYWJNN0uQCg?t=21)

## M01002. Operator Precedence (★★)

```matlab
x = randi([1 14]); % returns an integer drawn from the interval [1, 14]
y = randi([1 14]); % returns an integer drawn from the interval [1, 14]
z = randi([1 14]); % returns an integer drawn from the interval [1, 14]
```

(a) Write a code to check if x lies in more than 5 and less than 10. If yes, assign 1 to 'l_a' and otherwise 0. 
(b) Write a code to check if y + 2 lies in less than 5 or more than 10. If yes, assign 1 to 'l_b' and otherwise 0. 
(c) Write a code to check if y + 2 is the same with x. If yes, assign 1 to 'l_c' and otherwise 0. 
(d) Write a code to check if x + y is more than z and less than 10. If yes, assign 1 to 'l_d' and otherwise 0.

**Solution**
Please watch this:[**https://youtu.be/nYWJNN0uQCg?t=792**](https://youtu.be/nYWJNN0uQCg?t=792)

## M01003. Triangle Problem (★)


Given the variable lengths of 'A', 'B', 'C', determine whether a triangle with those sides lengths is a right triangle. 
Here, C is the hypotenuse: (https://en.wikipedia.org/wiki/Right_triangle).
Check to see if each side creates a right angle triangle when:


a) the lengths of 'A', 'B', and 'C' are 3, 4, and 5, respectively. If yes, assign true to 'tri_check_a', otherwise false. 
b) the lengths of 'A', 'B', and 'C' are 10, 5, and 12, respectively. If yes, assign true to 'tri_check_b', otherwise false. 
c) the lengths of 'A', 'B', and 'C' are 8,  6, and 10, respectively. If yes, assign true to 'tri_check_c', otherwise false. 

**Solution**
Please watch this:[**https://youtu.be/nYWJNN0uQCg?t=1424**](https://youtu.be/nYWJNN0uQCg?t=1424)

## M01004. Swap Three Numbers (★★) 

Sarah has a younger cousin Ellie in Grade 7, and her school is currently covering the content of right-angle triangles. However, 
Ellie is very bad at remembering names, and she always interprets a hypotenuse side as an adjacent side, an adjacent side as an opposite side,
and an opposite side as a hypotenuse side. One day Sarah was checking Ellie's math assignment, and she found out Ellie made this kind of mistake again. 
Please correct Ellie's mistake and assign the right values for 'hypo', 'adj', and 'oppo'.
Here, the values for 'hypo', 'adj', and 'oppo' are randomly generated, which are written by Ellie.
(e.g. The mistake she made is that she assigned the value of hypotenuse to adjacent etc.) 


**Solution**
Please watch this:[**https://youtu.be/nYWJNN0uQCg?t=2001**](https://youtu.be/nYWJNN0uQCg?t=2001)

## M01005. Arithmetic Operations (★)

Suppose you are trying to build a tree house with metric tools using imperial instructions (no metric instruction).
Note that 'N','G','A','B' are all random variables in this question.


a) The first step of the instructions asks you to make the walls N inchs. What would be the length of the walls from the instructions if you were to convert them in cm? 
Please assign the value to the variable named as 'side_length'. 
b) Next, the instruction manual asks to make the walls G feet tall. How tall are the walls in meters? 
Please assign the value to the variable named as 'side_height'. 
c) Afterwards you are asked to make rectangular windows. The base of the windows are A inch(s) while the height is B inch(s). 
What will be the area (in cm^2) of the windows? 
Please assign the area value to the variable named as 'window_area'. 

**Solution**
Please watch this:[**https://youtu.be/nYWJNN0uQCg?t=2271**](https://youtu.be/nYWJNN0uQCg?t=2271)

## M01006. Rounding Function (★★) 

```matlab
% https://www.mathworks.com/help/matlab/ref/randi.html
x = randi([-20 20]); % returns an integer drawn from the interval [-20, 20]
y = randi([-20 20]); % returns an integer drawn from the interval [-20, 20]
```
(a) Write a script to compute a quotient when you divide x by y without using rem(x,y). The quotient should be stored in 's_a'. 
(b) Write a script to compute a remainder without using rem(x,y) function when you divide x by y. The remainder should be stored in 's_b'. 
Note that x and y are given. 

**Solution**
```matlab
% https://www.mathworks.com/help/matlab/ref/randi.html
x = randi([-20 20]); % returns an integer drawn from the interval [-20, 20]
y = randi([-20 20]); % returns an integer drawn from the interval [-20, 20]

%(a)
s_a = fix(x/y);

%(b)
s_b = x-s_a*y;
```

## M01007. Swap Numbers (★★)

For a field surveying trip, a  surveying team was required to measure the elevations of a few locations. 
We create variables called elev_A, elev_B, elev_C, and elev_D, and assign the corresponding elevation values to them.
Here, the values for 'elev_A', 'elev_B', 'elev_C', and 'evel_C', 'elev_D' are randomly generated. 
However, it turned out that one of the members misread the numbers (i.e. the value of location A was assigned to elev_D, the value of location B was assigned to
elev_A, the value of location C was assigned to elev_B,  the value of location D was assigned to elev_C, etc.) 
Please fix this problem and assign the right elevation values to the corresponding variables.

**Solution**

```matlab
elev_A = randi(100); % a random scalar integer between 1 and 100
elev_B = randi(100); % a random scalar integer between 1 and 100
elev_C = randi(100); % a random scalar integer between 1 and 100
elev_D = randi(100); % a random scalar integer between 1 and 100

tmp = elev_D;% temporary assign variables
elev_D = elev_C;
elev_C = elev_B;
elev_B = elev_A;
elev_A = tmp;
```

## M01008. Arithmetic Operation (★)

It is your first time driving a car and you are figuring out how the car pedals work in a 1999 Honda Civic. You press the gas pedal a third of the way and you accelerate at 7 m/s^2.  Answer the following questions:
a) You keep your foot in the same position for a random 10-20 seconds and then release all applied pressure from the gas pedal. Note that 'time' is a random variable, which is the time for acceleartion.  
If you assume there is no friction on the road, what velocity would you be going after you take your foot off the gas pedal? (use 'velocity' for your variable). The unit of the velocity is m/s. 
b) If the mass of the car is 1.143 tonnes, what is the force generated from the car? (use 'force' for your variable)
c) Your mother then asks you to go to an empty parking lot where she asks you to drive at constant velocity in a circle with a radius randomly between 5 to 10m. Since you love physics, you start to wonder "what is the maximum velocity that you can go before the tires start to slip?" Assign the value to 'v_max'. Assume the following:
- Centripital force (Fc): mass * velocity^2 / radius.
- Coefficient friction is 0.3
- Gravity is 9.81 m/s^2
Here, 'radius' is a random variable. 

**Solution**

```matlab
% a)
time=randi([10,20],1); %s
accel = 7; %m/s^2

% what's the velocity?
velocity= time*accel;

% b)
mass_car = 1.143; % ton

% what's the force?
conv_ton_kg = 1000;
force = mass_car*conv_ton_kg*accel;

% c)
g = 9.81; % gravity: m/s^2
coef= 0.3; % no unit
radius =randi([5,10], 1); % radius of a circle: m

f_fric = mass_car * g *coef * conv_ton_kg; % friction force: N
v_max = sqrt(f_fric*radius/(mass_car*conv_ton_kg))
```

## M01009. rem Function (★) 

In January of 2020, there was a presentation competition called "Living Planet @campus", which was sponsored by WWF. Helena heard that there were 1200~1300  individuals who submitted their applications. The organizer wanted to divide them into a group of 3, 4, or 5. In order to promote fair competition, they wanted to make sure 
the number of members of each group is the same. You are going to write a script to check if they can make this possible? Create three variables, 'test_3', 
'test_4', and 'test_5' to check if the partipants can be exactly divided into gorups of 3, 4, or 5 (Each group is required to have the same number of members).
The number of participants is randomly generated in the given code. Note that your ouput for these variables is required to be logical (either a logical 0 or a logical 1).

**Solution**

```matlab
num_parti = randi([1200 1300],1); % # of participants

test_3 = rem(num_parti,3) == 0;
test_4 = rem(num_parti,4) == 0;
test_5 = rem(num_parti,5) == 0;% tests to check of the number of participants can be divisible by 3, 4, or 5
```
## M01010. Type Casting and rem Function (★★)

Karen is obsessed with gashapon Machines, which would give you one candy capsule with a different number of candies each time when you play them.  The number of 
candies in a capsule would be 1~20. One day, Karen was with two of her friends, and they played the machine for 4 times. Four variables, called cap1, cap2, cap3, 
and cap4, were the number of candies in the capsule each time they got from the machine respectively. They wanted to split the candies equally every round. Create 
four variables, lg1, lg2, lg3, and lg4 (type logical), to test if they cannot split the candies equally every round. Assign logical 1 in each variable if they cannot 
split the candies equally. Also, create a variable called num_3 to count how many times out of these 4 rounds they cannot split their candies equally.

```matlab
cap1 = randi([1 20],1);
cap2 = randi([1 20],1);
cap3 = randi([1 20],1);
cap4 = randi([1 20],1); %the number of candies in the capsule each time (randomly generated)

% write your code here
lg1 = rem(cap1,3) ~= 0;
lg2 = rem(cap2,3) ~= 0;
lg3 = rem(cap3,3) ~= 0;
lg4 = rem(cap4,3) ~= 0;
num_3 = lg1 + lg2 + lg3 +lg4;
```
