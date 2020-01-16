# OOP3 readme
Welcome to the OPP3 project wiki of Tomer, Michael and Avi! We are students at Ariel University. Over the last few weeks we have created a project that deals with Graph algorithms. In the project, we created a game that has several fruits that are eaten by robots(In the shortest route). There are two options of computer game - manual or automatic.



# Main classes:
1.DGraph (datastructure)
2.Edge (datastructure)
3.GamePar (gameClient)
4.Graph_Algo (algorithms)
5.myFruit (gameClient)
6.myRobot (gameClient)
7.MyGameGUI




# DGraph class: 
This class is an implements represents a directional weighted graph. The class has a road-system or communication network in mind - and should support a large number of nodes (over 100,000).


List of functions:
node_data getNode, edge_data getEdge, addNode, connect, Collection, node_data removeNode, edge_data removeEdge, nodeSize, edgeSize, getMC

 
# GamePar class:
This class is an implements of Game_par class.

List of functions:
GamePar, initFruit, getedges, initRobot, numRobot, fruit_edges, getfruit, getrobot.


# myFruit class:

This class is an implements of Fruits class.

List of functions:
myFruit, setedges, edge_data, getValue, getLocation, getType, toString, initFromJson.



# myRobot class:

This class is an implements of Robots class.

List of functions:
myRobot, getValue, getLocation, getSrc, getId, getDest, getSpeed, toString, setDest, setSrc, setLocation, botFromJSON




# MyGameGUI class: 
In this class, we used stddraw's library. Through this class, we create the gui.

List of functions:
MyGameGUI, initGUI, paint, setTime, result, actionPerformed, mousePressed, setG, setFr, setrb, setFr_Edge



# Graph_Algo class: 

This class is an implements represents the "regular" Graph Theory algorithms.

List of functions:
init,cleanGraf, save, isConnected, shortestPathDist, shortestPath, TSP, copy

Issues:
Function Name: TSP We can't really complete the TSP without checking all the possibilities, but checking them will cost too much time.

