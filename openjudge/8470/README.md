# P1200:DNA

------

总时间限制: 6000ms 内存限制: 1024kB

### 描述

考虑一段DNA单链，上面有N个基因片段。这里的基因片段可重叠（例如AGCTC包含AGC和CTC），不可倒置（例如AGCTC不包含TCG）。要问这样的单链最短长度是多少。

### 输入

输入的第一行是一个正整数T（不超过13），表示数据组数。每组数据若干行，其中第一行一个正整数N（不超过9），表示基因片段的数目，接下来N行每行一个基因片段，由AGCT四个字母组成，且长度介于1和15之间（含两端）。

### 输出

每组数据输出一样，表示最短的单链长度包含这N个基因片段。<br>

### 样例输入

1
5
TCGG
GCAG
CCGC
GATC
ATCG

### 样例输出

11