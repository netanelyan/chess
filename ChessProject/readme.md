\# Chess Project ♟️  

A full object-oriented C++ implementation of chess, built as part of the Magshimim program.



\## 📌 Overview

\- A `Board` class that stores piece positions  

\- A hierarchy of chess pieces (`King`, `Queen`, `Rook`, `Bishop`, `Knight`, `Pawn`)  

\- A `Location` class for handling board coordinates  

\- Move validation for each piece type  

\- Detection of legal and illegal moves  



The focus of the project is on \*\*OOP design\*\*, inheritance, and encapsulation.



---



\## 📂 Project Structure



ChessProject/

│ Board.h / Board.cpp

│ Piece.h / Piece.cpp

│ King.h / King.cpp

│ Queen.h / Queen.cpp

│ Rook.h / Rook.cpp

│ Bishop.h / Bishop.cpp

│ Knight.h / Knight.cpp

│ Pawn.h / Pawn.cpp

│ Location.h / Location.cpp

│ main.cpp (if exists)

│ README.md





Each piece class overrides virtual functions from `Piece` to implement its movement rules.



---



\## 🚀 How to Run



1\. Open the project in \*\*Visual Studio / VSCode\*\*.

2\. Make sure all `.cpp` files are included in the project.

3\. Build and run:

g++ \*.cpp -o chess

./chess





---



\## 🧠 Features Implemented

\- Full chess movement logic  

\- Validation of moves:

\- Straight-line movement (rook)

\- Diagonals (bishop)

\- L-shape (knight)

\- Combined movement rules (queen)

\- Special king movement  

\- Pawn movement + capture rules  

\- Board display in console  

\- Error codes for invalid moves (as required by Magshimim)



---



\## 📝 Notes

\- The project follows the Magshimim C++ OOP assignment guidelines.  

\- Some advanced rules (check, checkmate, castling, en passant) may not be implemented unless required.  

\- All code uses clean OOP style with headers, CPP files, and proper class separation.



---



\## 📧 Author

Natanel Yan  

Magshimim Program – Year 2



