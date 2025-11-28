# Library-management-system
Tarun Moolchandani
24BCE11235

A Java Console Application to manage library operations. This project demonstrates state management (Books being Available vs Borrowed) and association between objects.

## 🚀 Features
- *Catalog Management:* Add new books with ID, Title, and Author.
- *Member Management:* Register new library members.
- *Borrowing Logic:* - Prevents borrowing if the book is already taken.
  - Updates book status to [Borrowed].
- *Return Logic:* Updates book status back to [Available].

## 🛠 How to Run
1. Clone the repo.
2. Compile: javac Main.java
3. Run: java Main

## 📚 Technical Concepts
- *OOP:* Encapsulation (Private fields), Interaction between classes (Library manages Book).
- *Collections:* Uses ArrayList to store dynamic data.
- *State Handling:* Boolean flags track book availability.
