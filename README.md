# chess_problem

This is a Python answer to a problem based on chess, stated as follows.

Starting with a standard chess board measuring 8 by 8 squares, and numbered as below:
<table>
<tr>																							
<td>	0	</td>	<td>	1	</td>	<td>	2	</td>	<td>	3	</td>	<td>	4	</td>	<td>	5	</td>	<td>	6	</td>	<td>	7	</td>
</tr>																							
<tr>																							
<td>	8	</td>	<td>	9	</td>	<td>	10	</td>	<td>	11	</td>	<td>	12	</td>	<td>	13	</td>	<td>	14	</td>	<td>	15	</td>
</tr>																							
<tr>																							
<td>	16	</td>	<td>	17	</td>	<td>	18	</td>	<td>	19	</td>	<td>	20	</td>	<td>	21	</td>	<td>	22	</td>	<td>	23	</td>
</tr>																							
<tr>																							
<td>	24	</td>	<td>	25	</td>	<td>	26	</td>	<td>	27	</td>	<td>	28	</td>	<td>	29	</td>	<td>	30	</td>	<td>	31	</td>
</tr>																							
<tr>																							
<td>	32	</td>	<td>	33	</td>	<td>	34	</td>	<td>	35	</td>	<td>	36	</td>	<td>	37	</td>	<td>	38	</td>	<td>	39	</td>
</tr>																							
<tr>																							
<td>	40	</td>	<td>	41	</td>	<td>	42	</td>	<td>	43	</td>	<td>	44	</td>	<td>	45	</td>	<td>	46	</td>	<td>	47	</td>
</tr>																							
<tr>																							
<td>	48	</td>	<td>	49	</td>	<td>	50	</td>	<td>	51	</td>	<td>	52	</td>	<td>	53	</td>	<td>	54	</td>	<td>	55	</td>
</tr>																							
<tr>																							
<td>	56	</td>	<td>	57	</td>	<td>	58	</td>	<td>	59	</td>	<td>	60	</td>	<td>	61	</td>	<td>	62	</td>	<td>	63	</td>
</tr>																																																															
</table>

Given any 2 positions on the board <i>source</i> and <i>destination</i>, calculate the shortest number of moves that the knight would take to move between the 2 squares.

#### For example

```python
answer(src = 9, dest = 26)
````
returns

<code>1</code>


```python
answer(src = 0, dest = 0)
````
returns

<code>0</code>


```python
answer(src = 19, dest = 42)
````
returns

<code>2</code>
