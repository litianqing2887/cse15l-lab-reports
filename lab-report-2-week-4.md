# **First Change**
![change1](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/change_1.png?raw=true)
[test_file](https://litianqing2887.github.io/markdown-parse/test.md) 

*input: java MarkdownParse test.md*

*output: infinite 13*

After all the open brasket had accessed, the indexOf() method will return -1 to currentIndex. So, in every loop, currentIndex becomes -1 and then 13 and is printed. The loop should break if there is no more open brascket. 
