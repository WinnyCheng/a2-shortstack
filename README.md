Assignment 2 - Short Stack: Basic Two-tier Web Application using HTML/CSS/JS and Node.js  
===
## Random Drawing Generator

The website is a generator that creates a 3D image using multiple triangles. The User inputs the number of vertices (number of points) and the number of triangles to draw. It randomly generates the (x, y, z) coordinates for a specificed number of points and draws the specificed number of triangles from randomly picked points. The generated drawing is displayed on the right. The last input is for giving the creation a name. The user can also translate and rotate the drawing using special characters: !, @, #, $, %, ^, and &.

https://winnycheng-a2-shortstack.glitch.me/

## Technical Achievements
- **Random Number Generation**: Generated random x, y, z values (ranging from -1 to 1) for n number of vertices (points) specified by the user. Randomly pick out of those points to form x number of triangles also specified by the user. The first two on the list (Cube and Triangular Pyramid) was not randomly generated. They are specified points and triangles made by me. (If they are unedited. If edited, the points and triangles will be replaced by random generated ones.)
- **Implementing a 3D drawing canvas using WebGL**: Transforming an old WebGL project to draw a 3D object based on randomly generated coordinates and randomly picked coordinates to form multiple triangles to form a triangle mesh. 


### Design/Evaluation Achievements
- **Adding view button**: Redraws (can view) any other creations in the data list.  
- **Self wrote CSS code**: Colors, Font, format was all manually written. Used flex and grid to format page. Exernal templates were not used. 

Ching Wing (Winny) Cheng 
