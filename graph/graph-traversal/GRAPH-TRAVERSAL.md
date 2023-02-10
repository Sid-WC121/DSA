<p align="right">
<kbd>
<a href="https://github.com/Sid-WC121/DSA" >Main</a><br>
</kbd>
<kbd>
<a href="https://github.com/Sid-WC121/DSA/blob/main/graph/spanning-tree/SPANNING-TREE.md" >next(Spanning Tree)</a>
</kbd>
</p>
<h1 align="center">Graph Traversal</h1>
<br>

<p align="auto"> It's the process of visiting each vertex in a graph. There are two standard methods.</p>

1. BFS ( *Breadth First Search* )
2. DFS ( *Depth First Search* )

## :one: BFS ( *Breadth First Search* )

<p></p>

## :two: DFS ( *Depth First Search* )

<p> DFS produces a spanning tree as an final result , i.e <em> a graph without loops </em>.We uses a stack with maximum size of total no of vertices in the graph to implement the DFS</p>
  
`psuedocode`
```
DFS(G,v)   ( v is the vertex where the search starts )    
        Stack S := {};   ( start with an empty stack )    
        for each vertex u, set visited[u] := false;    
        push S, v;    
        while (S is not empty) do    
           u := pop S;    
           if (not visited[u]) then    
              visited[u] := true;    
              for each unvisited neighbour w of uu    
                 push S, w;    
           end if    
        end while    
     END DFS()    
```

<p align="right">
<kbd>
<a href="https://github.com/Sid-WC121/DSA/blob/main/graph/spanning-tree/SPANNING-TREE.md" >next(Spanning Tree)</a>
</kbd>
</p>
