[![Run on Repl.it](https://repl.it/badge/github/youpeterabb1t/codingtest)](https://repl.it/github/youpeterabb1t/codingtest)
1. 본인의 파이썬 실력은? 파이썬으로 코딩해본 경험
2. 프로그래밍 1,2, 문해방 외에 프로그래밍 수업 수강했는지?
3. 웹 서비스 개발 해본적 있는지
4. DB 사용해서 프로그래밍 해본적 있는지
5. GoogleAPI나 다른 API 사용해본적 있는지


<H1>#CodingTest</H1>

<H1>#1</H1>
<p>Create a function to return the list "L" containing "N" numbers of random positive integers. 
At the same time, the average of list "L" should be A.
</p>
Example code below
----------------------------------------------
	import random
	import numpy as np

	def averize(N,A):
		L=[]
		"""
		fill in the blank
		"""

		return L

<H2>TEST CASE</h2>
<P>
N=100, A= 2.65
N=1000, A=3.754

!Return type should be "list"
</P>
<h2>Result</h2>
--------------------------------------
	print(np.mean(averize(100,2.65)))
>>>2.65
	print(np.mean(averize(1000,3.754)))
>>>3.754


<H1>#2</H1>
<p>
Write a program to find out how many times each number is written from 0 to 9 in the calculation result of A × B × C 
when three natural numbers A, B, and C are given.

For example, A = 150, B = 266, C = 427
A × B × C = 150 × 266 × 427 = 17037300,

As a result of calculation, 0 is 3 times, 1 is 1 time, 3 is 2 times, and 7 is 2 times in 17037300.
</p>
<H2>Input</H2>
A is given in the first row, B in the second row, and C in the third row. A, B, and C are all natural numbers less than or equal to 100 and less than 1,000.

<H2>Output</H2></br>
<p>
The first line prints how many times 0 was written in the result of A × B × C. Likewise, from the second row to the tenth row, the number of digits 1 through 9 is written in the result of A × B × C, one by one in turn.</p>
<H3>Result</H3>
-----------------------------------</br>
3</br>
1</br>
0</br>
2</br>
0</br>
0</br>
0</br>
2</br>
0</br>
0</br>
