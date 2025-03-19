# Personal Library Manager (CLI-Based)

## 📖 Overview
The **Personal Library Manager** is a command-line interface (CLI) application built using Python. It allows users to efficiently manage their book collection by adding, updating, searching, and deleting books. Additionally, users can track their reading progress with a simple and intuitive interface.

## 🚀 Features
- 📚 **Add Books**: Store book details such as title, author, publication year, genre, and reading status.
- 🗑 **Remove Books**: Delete a book from the collection by its title.
- 🔎 **Search Books**: Find books by title or author.
- ✏ **Update Books**: Modify book details, including title, author, year, genre, and reading status.
- 📂 **View All Books**: Display the entire book collection.
- 📊 **Track Reading Progress**: View statistics on books read and completion rate.
- 💾 **Persistent Storage**: All books are stored in a JSON file (`books_data.json`) for future access.

## 🛠 Installation & Setup
### Prerequisites
- Python 3.x installed on your system

### Steps to Run the Application
1. **Clone the repository**
   ```sh
   git clone https://github.com/abdulrahman-58/personal_library_manager.git
   cd library-manager
   ```
2. **Run the script**
   ```sh
   python book_manager.py
   ```

## 📌 How to Use
Once you run the script, you will see a menu with options:
1. **Add a new book** → Input book details to store it in the collection.
2. **Remove a book** → Enter the book title to delete it.
3. **Search for books** → Search by title or author.
4. **Update book details** → Modify an existing book's details.
5. **View all books** → Display the complete list of books.
6. **View reading progress** → Show statistics on books read.
7. **Exit** → Quit the application.

## 📂 Data Storage
All books are saved in a JSON file (`books_data.json`). If the file is missing or corrupted, a new file will be created.

## 📜 License
This project is licensed under the MIT License.
