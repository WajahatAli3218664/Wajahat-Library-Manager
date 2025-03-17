Here’s a well-structured and professional **README.md** file for your project, tailored to your requirements. Replace placeholders like `Your Name` and `yourusername` with your actual details.

---

# 📚 Personal Library Manager 📚

Welcome to the **Personal Library Manager**, created by **Your Name**! This is a simple command-line tool designed to help you manage your book collection. With this program, you can add, remove, search, and view statistics about your books. The library is automatically saved to a file (`library.txt`) and loaded when you restart the program.

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
   git clone https://github.com/yourusername/library-manager.git
   cd library-manager
   ```

2. **Run the Program**:
   Ensure Python is installed on your system. Then run:
   ```bash
   python library.py
   ```

---

## 📋 Usage

1. Run the program using the command:
   ```bash
   python library.py
   ```

2. Follow the menu prompts to interact with your library:
   - Add books, remove books, search for books, or view statistics.
   - The program will automatically save your library to `library.txt` when you exit.

---

## 📝 Sample Output

Below is an example interaction with the program:

```plaintext
D:\library-manager>python library.py
🌟 Welcome to your Personal Library Manager! 🌟

📋 Menu:
1. ➕ Add a book        
2. ➖ Remove a book     
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 5

📊 No books in the library. Add some books! 📊

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 1
📝 Enter the book title: The Great Gatsby
🖋️ Enter the author:  F. Scott Fitzgerald
📅 Enter the publication year: 1925
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
👉 Enter your choice: 1
📝 Enter the book title: 1984
🖋️ Enter the author:  George Orwell
📅 Enter the publication year: 1949
🎭 Enter the genre: Dystopian
✅ Have you read this book? (yes/no): no
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
1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - 📖 Read
2. 1984 by George Orwell (1949) - Dystopian - ❌ Unread

📋 Menu:
1. ➕ Add a book
2. ➖ Remove a book
3. 🔍 Search for a book
4. 📚 Display all books
5. 📊 Display statistics
6. 🚪 Exit
👉 Enter your choice: 5

📊 Total books: 2
📊 Percentage read: 50.0% 📊
```

---

## 📁 File Structure

```
library-manager/
│
├── library-manager.py     # Main Python script for the library manager
├── library.txt     # File to store the library data (automatically created)
└── README.md       # Instructions and notes about the project
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
