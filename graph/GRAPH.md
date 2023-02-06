<h1 align="center"> Graph Terminologies</h1>
<br>

<h2> :sparkle: Introduction to Graph </h2>
<p> A graph is a mathematical representation of a set of objects and the connections or relationships between them. It consists of two main components: vertices (also known as nodes) and edges. It a non-linear data structure <p>
<h2 align="center">graph = nodes + edges</h2>

- Vertices represents the entities, vertices are also known as vertex or nodes.
- Edges represents the relationship between the entities. An edge can be directed or undirected. 

<p> Mathematicaly we can also say that a graph G is an ordered pair of a set V of vertices and set E of edges <p>
<h2 align="center"> G = ( V, E ) </h2>
<p> In computer science, graphs are commonly used in data structures, such as trees and networks, and in algorithms, such as search algorithms and pathfinding algorithms. They are also used in machine learning and artificial intelligence.</p>
<h2>:pirate_flag: Types of Graph </h2>

<h2>:one: Undirected Graph </h2>
<p> It is a graph <b> G </b> in which the edges does'nt have any direction.<br></p>
<p align="center">
<img src="/graph/undirected.jpg" alt="Undirected graph" style="height: 200px; width:200px;"/>
</p>
<h2 align="center">a<sub>ij</sub> = a<sub>ji</sub>
<br>
  
<h2>:two: Directed Graph </h2>
<p> It is a graph <b> G </b> in which the edges possess direction.<br></p>
<p align="center">
<img src="/graph/directed.jpg" alt="Directed graph" style="height: 200px; width:200px;"/>
</p>
<h2 align="center">a<sub>ij</sub> ≠ a<sub>ji</sub>
<br>
  
<h2>:three: Weighted Graph </h2>
<p> It can be directed or undirected  graph <b> G </b>edges have a numerical value(weight).</p>
  
  - <h4>Weighted Directed Graph: <em>A directed graph with edge weight</em> or <em>A weighted and directed graph is where edges have a direction and a numerical value!</em></h4>
<p align="center">
<img src="/graph/wdg.jpg" alt="Directed graph" style="height: 230px; width:250px;"/>
</p>
  
  - <h4>Weighted unDirected Graph: <em>An undirected graph with edge weight</em></h4>
<p align="center">
<img src="/graph/wudg.jpg" alt="Directed graph" style="height: 230px; width:250px;"/>
</p>
<br>
 
<h2>:four: Cyclic Graph </h2>
<p>A graph that contains at least one cycle is known as a cyclic graph.</p>
<p align="center">
<img src="/graph/cyclic.jpg" alt="Directed graph" style="height: 200px; width:200px;"/>
</p>
<br>

<h2>:five: Acyclic Graph </h2>
<p>A graph that contains zero cycles is known as an acyclic graph.</p>
<p align="center">
<img src="/graph/acyclic.jpg" alt="Directed graph" style="height: 200px; width:200px;"/>
</p>
<br>
<p align="center">
<img src="/graph/DCG.jpg" alt="Directed graph" style="height: 250px; width:500px;"/>
</p>
<br>
  
> Note:
> <p> A cycle in context of graph occures when number of vertices are connected to one another in a closed chain of edjes.<p>
  
<h2>:six: Directed aCyclic Graph (DAG) </h2>
<p>A directed aCyclic graph ia one that is directed, but does not contain ANY cycles. These are also called DAG's for short.</p>
<p align="center">
<img src="/graph/DAG.jpg" alt="Directed graph" style="height: 200px; width:200px;"/>
</p>
<br>

> Note:
> - A DAG is the backbone of applications that handle scheduling for system of tasks, which needs to be processed in an order.<br>
> - It is the concept behind Dependency Graphs.<br>
> - It is used to represent a State Machine for objects that don't have " reversible " states.

<h2>:seven: Degree of a Vertex</h2>
<br>

<h2>:eight: Degree of a Graph </h2>
<br>

<h2>:nine: Connected Graph </h2>
<br>

<h2>:keycap_ten: Disconnected Graph </h2>
<br>
