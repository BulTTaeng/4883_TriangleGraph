# 4883_TriangleGraph

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/4883_TriangleGraph/blob/main/4883_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

Find how to solve was easy but implementation was little bit hard.

Everybody will know that saving the min cost until now will work.

However in second depth, (input[1][0] ,input[1][1], input[1][2]) we have to save the min value staring from input[0][1].

Moreover , because problem is saying that the input is int type, input can be minus. It means we have to search all case.

In second depth, there is 3 ways to reach the input[1][1]

4 ways to reach the input[1][2]

After that , find every possible way to reach some location and find the min will be the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
