The following details steps on setting up OpenGL on Windows using Visual Studio:

  1) Download freeglut and glew:
    * Glut: http://freeglut.sourceforge.net/
    * GLEW: http://glew.sourceforge.net/

  2) Open Visual Studio

  3) Make a new Visual C++ Empty project and name it appropriately

  4) In the solution explorer, right click the project (displayed in bold) and select properties

  5) Under C/C++, select Additional Include Directories
    * Click on the dropdown icon on the right

  6) Add the directories to the include folders
    * Go down to include folder
    * Example: glew-1.11.0\include and freeglut\include

  7) Under Linker, select Input
    * Click on the dropdown icon on the right

  8) Under additional dependencies, enter:
    * freeglut.lib
    * glew32.lib
    * Note the names depend on the file with the .dll file extension

  9) Under Linker, select general

  9) Under additional Library Directories, enter the destination to the library folders
    * Go down to lib folder
    * Example: glew-1.11.0\lib and freeglut\library

  10) Click apply and hit Ok.
