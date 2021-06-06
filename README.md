# Android-Studio-LocalDataBase-With-Room
1. Create an Activity with a FrameLayout inside.
2. Configure Room/Firebase Database library;
3. Create a fragment which contains the following:
- One EditText with hint “Book Title” (max 100 characters, validate to be non-empty); 
- One EditText with hint “Book Author” (max 100 ch, validate to be non-empty);  
- One EditText with hint “Book Description” (max 1000 ch, validate to be non-empty); 
- 1 Button below 3rd EditText. It will be used to ADD/UPDATE (if title+author exists) a Book into Room/Firebase Database if validations on edittexts passes - otherwise, show error message.
- RecyclerView to load all the books.
4. Inside RecyclerView, book layout cell will contain the following: 
- Title - max 1 lines, ellipsize - end;
- Author - max 1 line, ellipsize - end;
- Description - max 3 lines, ellipsize - end;
- Delete button/icon used to remove the book from recyclerview & database.
5. When click on a book, open a new fragment that displays book details.
