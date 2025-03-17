# 📚 Personal Library Manager 📚

Welcome to the **Personal Library Manager**, created by **Wajahat Ali**! This is a simple command-line tool designed to help you manage your book collection. With this program, you can add, remove, search, and view statistics about your books. The library is automatically saved to a file (`library.txt`) and loaded when you restart the program.

---

## 🌟 Features

- **Add a Book** ➕: Add new books to your library with details like title, author, publication year, genre, and read status.
- **Remove a Book** ➖: Remove books from your library by their title.
- **Search for a Book** 🔍: Search for books by title or author.
- **Display All Books** 📚: View all the books in your library in a formatted list.
- **Display Statistics** 📊: Get insights into your library, such as the total number of books and the percentage of books you've read.
- **Save and Load Library** 💾: Automatically saves your library to `library.txt` and loads it when you restart the program.

---

## 🛠️ Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/WajahatAli3218664/Wajahat-Library-Manager
   cd library-manager
   ```

2. **Run the Program**:
   Ensure Python is installed on your system. Then run:
   ```bash
   python library-manager.py
   ```

---

## 📋 Usage

1. Run the program using the command:
   ```bash
   python library-manager.py
   ```

2. Follow the menu prompts to interact with your library:
   - Add books, remove books, search for books, or view statistics.
   - The program will automatically save your library to `library.txt` when you exit.

---

## 📝 Sample Output

Below is an example interaction with the program:

```plaintext
🌟 Welcome to your Personal Library Manager! 🌟

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book      
3. 🔍 Search for a book 
4. 📚 Display all books 
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 1
📝 Enter the book title: Harry Potter and the Philosopher's Stone
🖋️ Enter the author:  J.K. Rowling                            
📅 Enter the publication year: 1997
🎭 Enter the genre: Fantasy
✅ Have you read this book? (yes/no): yes
🎉 Book added successfully! 🎉

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 1
📝 Enter the book title: The Name of the Wind
🖋️ Enter the author:   Patrick Rothfuss
📅 Enter the publication year: 2007
🎭 Enter the genre: Fantasy 
✅ Have you read this book? (yes/no): no
🎉 Book added successfully! 🎉

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 1
📝 Enter the book title: Basti
🖋️ Enter the author:  Intizar Husain
📅 Enter the publication year: 1979
🎭 Enter the genre: Fiction
✅ Have you read this book? (yes/no): yes
🎉 Book added successfully! 🎉

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 4

📚 Your Library: 📚
1. Harry Potter and the Philosopher's Stone by J.K. Rowling (1997) - Fantasy - 📖 Read
2. The Name of the Wind by Patrick Rothfuss (2007) - Fantasy - ❌ Unread
3. Basti by Intizar Husain (1979) - Fiction - 📖 Read

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 5

📊 Total books: 3
📊 Percentage read: 66.67% 📊

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 6
💾 Library saved to file. Goodbye! 👋
```

---

## 📁 File Structure

```
library-manager/
│
├── library-manager.py     # Main Python script for the library manager
├── library.txt            # File to store the library data (automatically created)
└── README.md              # Instructions and notes about the project
```

---

## 🤝 Contribution

Feel free to contribute to this project by opening issues or submitting pull requests. Suggestions for improvement are always welcome!

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### About the Author

This project was created by **Wajahat Ali** as part of a learning exercise. If you have any questions or feedback, feel free to reach out!

---

Enjoy managing your library! 📚✨
