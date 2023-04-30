Download Link: https://assignmentchef.com/product/solved-icsi403-homework-3
<br>
The objective of this assignment is to implement two different algorithms for the minimum spanning tree problem and experimentally compare their computation times. The required background material is in Chapter 23, but in the following you will explicitly be given the necessary pseudo code.




An undirected graph consists of nodes and edges. Each edge has a cost associated with it. An example of an undirected graph with edge costs is shown below.







In the above figure, nodes are represented by circles and edges are represented by lines. The integer labeling each edge is the cost of that edge. (Note that nodes are numbered from 0.) The graph is connected; that is, we can go from any node to any other node using only the given edges.




A spanning tree for a connected graph is a tree that connects all the nodes. Such a tree uses a subset of the edges of the graph, and the cost of the tree is the sum of the costs of all the edges included in the tree. Figure 2 shows two spanning trees for the graph of Figure 1. Note that the

tree shown in Figure 2(b) has a lower cost than the tree shown in Figure 2(a).







A <strong>minimum spanning tree (MST)</strong> for a graph is a spanning tree whose cost is minimum among all the spanning trees. The tree shown in Figure 2(b) is an MST for the graph of Figure 1.




Several algorithms for finding an MST of a connected graph are known. You are required to implement two algorithms whose pseudo-codes are given below in this assignment. Examples to illustrate these algorithms and some implementation details will be presented in class.




Command line details: In your video you should demonstrate that your program runs through a driver class named DriverMST.class. It should be tested using the command line command: java DriverMST infile.txt

or using the command

java DriverMST infile.txt -e







where infile.txt represents the name of the input file which contains a description of the graph. <strong>Note: additional arguments specifying the class path might also be added. </strong>







The format of the input file is discussed below. Your program must run both the algorithms on the input graph and write to System.out.println(), the following information for each algorithm (each piece of information on a separate line):

<ol>

 <li>The execution time in ms (Please, refer back to programming assignment 1 to check how we timed parts of our programs.)</li>

 <li>The cost of the minimum spanning tree.</li>

 <li>If the -e option is specified on the command line, then the list of edges in the spanning tree along with the cost of each edge. (If the command line does not specify the -e option, then the list of edges should not be produced.)</li>

</ol>




Format of input file: The first line of the input file contains the number of nodes in the graph. This is followed by several lines, each specifying three positive integers separated by a space character. The first two of these integers specify the nodes joined by the edge and the third integer specifies the cost of the edge. For example, an input file to describe the graph of Figure 1 is as follows. 6

0 1 6

0 2 1

<ul>

 <li>3 10</li>

 <li>2 5</li>

 <li>4 3</li>

 <li>3 10</li>

</ul>

2 4 6

<ul>

 <li>5 4</li>

 <li>5 2</li>

 <li>5 9</li>

</ul>




You may assume that each input graph is connected and that it has at most 1000 nodes and at most 10,000 edges.




Your program should be well-structured and documented with comments. It should be compatible with Java 1.7 and later. Some sample inputs and outputs that you can use to test your program can be found as part of the assignment on BB. Your program should correctly identify the MSTs for the sample inputs, but it will be tested with other inputs as well.

Grading policy:

<ol>

 <li>If your program does not compile you will receive 0 points!</li>

 <li>If you don’t submit a video of your code compiling and running you receive a 0!</li>

 <li>If your program fails to read the provided test files and produce an output, you will lose points!</li>

 <li>Correct implementations of the two algorithms is required!</li>

 <li>Programs that achieve the correct result on all test cases will get full points!</li>

</ol>




<strong>You should not hard code the answers for provided test cases! </strong>




<strong>This is an independent assignment. Similarity to code on the Internet or to that of other students will result in zero points for involved students and reporting for academic dishonesty. </strong>

<strong>                </strong>

<strong> </strong>

<strong> </strong>

<strong>                </strong>

<strong> </strong>

<strong>                </strong>


