# AlgoServer
A multi-threaded server that can solve path-finding problems(in matrix)

The clients can send a path-finding problem(low cost to destination path) to the server(in a form of a matrix). The server solves the problem with a chosen algorithm(which is one of many algorithmes we implemented), stores the solution and send it to the client. When another client asks for soulutin, the server first checks if we already have a soulution, and if so, it sends it witout solving again.

------------
#### Input Template:

SIZE

start.x, start.y

end.x, end.y

first row elements(space seperated)

second row elements (space seperated)

...
#### Input Example:

3

0,0

2,2

1 2 3

4 5 6

7 8 9
