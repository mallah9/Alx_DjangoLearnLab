# Create a Book instance
book = Book.objects.create(
    title="1984", author="George Orwell", publication_year=1949
)

# Expected Output: Successfully created a new book object.
print(f"Book created: {book}")