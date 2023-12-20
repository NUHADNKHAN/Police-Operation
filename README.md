In this post, we will solve HackerRank Police Operation Problem Solution.

Roy is helping the police department of his city in crime fighting. Today, they informed him about a new planned operation.
Think of the city as a 2D plane. The road along the X-axis is very crime prone, because n criminals live there. No two criminals live at the same position.
To catch these criminals, the police department has to recruit some police officers and give each of them USD h as wages. A police officer can start his operation from any point a. drive his car to point b in a straight line, and catch all the criminals who live on this way. The cost of fuel used by the officer’s car is equal to the square of the euclidean distance between points a and b (Euclidean distance between points (x1,y1) and (x2, y2) equals to root(x1-x2)square + (y1-y2)square
The police department asks Roy to plan this operation. So Roy has to tell them the number of officers to recruit and the routes these officers should take in order to catch all the criminals. Roy has to provide this information while minimizing the total expenses of this operation.
Find out the minimum amount of money required to complete the operation.
Input Format
The first line contains two integers n (0 ≤ n ≤ 2 x 10 power 6), number of criminals, and h (0 <h< 109), the cost of recruiting a police officer. The next line contains n space separated integers. The ith integer indicates the position of the ith criminal on X-axis (in other words, if the ith integer is x, then location of the ith criminal is (x, 0)). The value of the positions are between 1 and 109 and are given in increasing order in the input.

Output Format

Print the minimum amount of money required to complete the operation.

Sample Input

5 10
1 4 5 6 9
Sample Output

34
Explanation
For the sample test case, police department recruits 3 officers who get paid 3 x 10 = 30. The first officer starts at point (1, 0) and catches the criminal there. So he does not use any fuel. The second officer catches criminals at points (4,0), (5,0) and (6, 0). He burns fuel worth USD 4. The third officer catches the criminal at point (9, 0). He also does not burn any fuel. The total money spent by the department is, 30+ 4 = 34,

