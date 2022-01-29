# **First Change**
![change1](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/change_1.png?raw=true)
[test_file1](https://litianqing2887.github.io/markdown-parse/MarkdownParse.java)
[test_file2](https://litianqing2887.github.io/markdown-parse/test.md) 

*input: java MarkdownParse test.md*

*output: infinite 13*

After all the open bracket had accessed, the indexOf() method will return -1 to currentIndex. So, in every loop, currentIndex becomes -1 and then 13 and is printed. The loop should break if there is no more open bracket. 


# **Second Change**
![change2](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/change_2.png?raw=true)
[test_file1](https://litianqing2887.github.io/markdown-parse/MarkdownParse.java)
[test_file2](https://litianqing2887.github.io/markdown-parse/test2.md)

*input: java MarkdownParse test2.md*

*output: hello link.html* However, "Hello" is not a link.

The contents between two parentheses after the close bracket are printed. However, these brackets and parentheses may not form the link syntax. The code should be aware that if there is a link syntax, which is an open parenthesis right after a close bracket. 


# **Thrid Change**
![change3](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/change_3.png?raw=true)
[test_file1](https://litianqing2887.github.io/markdown-parse/MarkdownParse.java)
[test_file2](https://litianqing2887.github.io/markdown-parse/test-file6.md)

*input: java MarkdownParse test-file6.md*

*output: page.com* However, "page.com" is a image, not a link. 

The syntaxes of link and image are similar. The code, which is supposed to print links only, prints the name of an image, without recognizing the "!" symbol behind the link syntax. The code should distinct the difference between links and images. 
