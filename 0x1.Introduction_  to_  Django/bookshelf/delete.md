# Delete the created book
book.delete()

# Expected Output: Delete successful. Confirm deletion.
books = Book.objects.all()
if not books:
    print("No books found. Deletion confirmed.")
else:
    print("Books still exist. Something went wrong.")