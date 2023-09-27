# Geometry-Game
### The Project Functions :
- There are some polygons
- All Polygons have different classes, functions
- It is in game mode, a player have to tell the area according to given information
- After Every level, The game becomes harder
- In every 5th level, Player has to tell sum of two different polygons

### Concepts of OOP used in the project:
1. There are total of 1 + 2 + 4 + 3 + 1 + 3 = 14 classes, initialized with constructors, have destructors
2. Three level inheritance is used here. Polygon -> (Quad, Tri, Any) -> (Rec, Sq, Prl, trp) (Equ, Iso, Sce)
3. Polymorphism is used : To Calculate Area - overiding the functions in derived classes
4. Abstract class and Pure Virtual Function is used : To Ask Question (In Game)
5. Friend class is used : To connect Polygon with Game, Gamer with Database
6. Friend function is used : To search player, To Run the game, For Home Page
7. STL is used : To sort co-ordinates anti-clockwise, sort Leaderboards, containers to store data
8. Operator Overloading : For input >> and output << for the gamer class
9. File Management : Database and Leaderboard - two files are used to read, write and store data
10. Template : This is used to add two polymorphic class using pointers and template function

### Lab Project by 
> Kazi Rifat Al Muin, 2107042, CSE, KUET
