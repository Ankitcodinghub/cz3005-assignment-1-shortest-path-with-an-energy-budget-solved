# cz3005-assignment-1-shortest-path-with-an-energy-budget-solved
**TO GET THIS SOLUTION VISIT:** [CZ3005 Assignment 1-Shortest Path with An Energy Budget Solved](https://www.ankitcodinghub.com/product/cz3005-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114296&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CZ3005 Assignment 1-Shortest Path with An Energy Budget  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Finding a Shortest Path with An Energy Budget

Assignment 1

1. Problem description

Figure 1: A small example.

Suppose we are given a graph with a predefined source node (𝑆𝑆) and a target node (𝑇𝑇). Each edge in the graph is associated with a pair of values (𝑋𝑋, 𝑌𝑌) where 𝑋𝑋 denotes the distance and 𝑌𝑌 denotes the energy cost. Also see Figure 1 for an illustration. The job is to find the shortest path between 𝑆𝑆 and 𝑇𝑇 such that the accumulated energy cost along the path does not exceed an energy budget. Specifically, we want to find the shortest path from Jurong East to Changi Airport not exceeding an energy budget 11. We can observe that although the path S-&gt;2-&gt;T has the shortest travel distance 10, its accumulated energy cost 12 exceeds the energy budget 11. Thus, this path is infeasible. In this example, the path S-&gt;1-&gt;T is the shortest feasible path.

1.1 Problem instance

You will be given a problem instance of New York city (NYC) road network of the United State. This instance is taken and modified from the 9th DIMACS implementation challenge. This instance has 264346 nodes and 730100 edges. You will be given four python dictionary files:

1.1.1 Graph dictionary G

The graph is given as an adjacency list where the neighbor list of node ‘v’ can be accessed with G[‘v’].

1.1.2 Node coordination dictionary Coord

The coordination of a node ‘v’ is a pair (X, Y) which can be accessed with Coord[‘v’]

1.1.3 Edge distance dictionary Dist

The distance between a pair of node (v, w) can be accessed with Dist[‘v,w’].

1.1.4 Edge cost dictionary Cost

The energy cost between a pair of node (v, w) can be accessed with Cost[‘v,w’.]

2. Requirements and guidelines

2.1 Tasks and marking criteria

You will need to solve three tasks that are listed as follow:

Task 1: You will need to solve a relaxed version of the NYC instance where we do not have the energy constraint. You can use any algorithm we discussed in the lectures. Note that this is equivalent to solving the shortest path problem. The solution quality of your algorithm will affect the grade.

Task 2: You will need to implement an uninformed search algorithm (e.g., the DFS, BFS, UCS) to solve the NYC instance.

Task 3: You will need to develop an A* search algorithm to solve the NYC instance. The key is to develop a suitable heuristic function for the A* search algorithm in this setting. The solution quality of your algorithm will affect the grade.

For tasks 2 and 3, the energy budget is set to be 287932. For all the 3 tasks, the starting and ending nodes are set to be ‘1’ and ‘50’, respectively.

2.2 Output format

The output of your algorithm should be formatted as the following (using Figure 1 as an example):

Shortest path: S-&gt;1-&gt;T.

Shortest distance: 12.

Total energy cost: 10.

2.3 Programming language

3. Teaming Formation

You are required to form a team of up to 3 people to complete this project. A team with only a single person is also allowed. For team size that is larger than one, you need to clearly state the contribution of each team member.

If you use any existing code, libraries, etc. and consult any papers, books, online references, etc. for your project, you must cite your sources in your report and clearly indicate which parts of the project are your contributions and which parts were implemented by others. Using others’ code/ideas without acknowledgement will lead to failure of your project.

5. Deliverables

You are required to produce:

(1) A final report of no more than 5 pages. Name your report as &lt;team name&gt;-final-report.pdf.

(2) Source codes for your project. Your source codes are to be submitted in .zip format. Name the zip file as &lt;team name&gt;-final-code.zip.

The following is a suggested structure for the report:

(1) Title, team members.

(2) For each task, explain your approach, output, etc.

(3) Contribution: Please clearly state the contribution of each team member if you have more than one member in your team.

(4) Conclusion: What have you learned?

(5) References: Please cite the sources you consulted in the report.

6. Submission

DSAI1, DSAI2, FS1, FS2 Xing Pengwei: PENGWEI001@e.ntu.edu.sg

TS1, TS2, TS7, TS8 Yang Fan: FAN007@e.ntu.edu.sg

FDDP1, TS6 Yu Wenhan: WENHAN002@e.ntu.edu.sg

DSAI3, TS3, TS5, TS9 Zhou Xinyu: XINYU003@e.ntu.edu.sg
