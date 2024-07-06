# DSA_Quests
A bit tricky Questions
A kingdom has N cities with M roads between them.
You are given a 2D array E denoting that there is a
road between the cities E[i][0] & E[i][1] and with a
distance of E[i][2] for 0<=i<=N-1
Bob loves traveling very much and wants to travel the
kingdom. He can start his trip from any city and end
the trip in any city he wants. However, he can't visit
the same city more than once.

You can perform the following operation exactly
once:
• Take one road with its distance and delete this
road. Add it in another place where there is no
road, provided that all cities remain connected to
each other(you can add the road in the same
place where it was removed).
Find the minimum distance of the longest trip that
Bob can take after performing the above given
operation.
Note:
• Its guaranteed that there is a path between every
two cities.
Input Format
The first line contains an integer. N. denoting the
number of cities in the kingdom.
The next line contains an integer, M, denoting the
number of rows in E.
The next line contains an integer, three, denoting the
number of columns in E.
Each line i of the M subsequent lines (where 0<= i < M)
contains three space separated integers each describing
the row E[i].

constraints:
1<=N<=2000
N-1<=M<=N-1
3<=three<=3
1<=E[i][i]<=10^5

exapmple:
input 
2
1
3
1 2 2

output: 2

explanation:

example:
Given N=3,M=2,three=3, E=[[1,2,1],[2,3,2]]
We can remove the road between cities 2,3
it between 1, 3. So the minimum distance
longest trip is 3.
3 and
of the
add

input: 
3
2
3
1 2 1
2 3 2

output: 3

explanation: Given N = 3, M = 2, three =
3 E=[[1,2,2],[1,3,3]]
We can remove the road between
cities 1, 2 and
add
it between 2, 3. So the minimum distance of the
longest trip is 5.
