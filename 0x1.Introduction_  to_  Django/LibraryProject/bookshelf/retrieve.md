# Retrieve all books (including the one you just created)
books = Book.objects.all()

# Expected Output: This will display all book objects, including details:
# <Book: 1984 (George Orwell) - 1949>
for book in books:
    print(book)