The code will be written and executed in Google colab
The topic of the project is Library Management System

The scope of the project will be as follows:

- There will be 2 types of users - admin and students
- Admin will login with username "admin" and password "admin123"
- Admin can add books, see the list of books, see which student has issued which book, see the list of pending returns, see the total amount of fine accumulated, and the feedback forms.

- Student can also login with roll number and password. The roll number should be unique and no 2 roll numbers can be the same. If a student enters a roll number that is not registered before, then a new registration is to be allowed with the roll number, name of the student and password.

- Students can see the list of books, but can issue books only if they have returned the previous book issued. The duration allowed for return is 28 days. If the duration gets over, then Rs. 10 for each day fine for every day late, till 15 days or Rs. 150. After that the student the fine reduces to Rs. 1 per day and the student is not allowed to issue any book for the next 60 days. If the duration of not returning exceeds 90 days, then the student is blocked from further issuing any books from the library forever.
- Student can also return books
- Student have access to a feedback form where they can tell if they want a new book in the library.

The program runs as follows:

- First it asks who wants to login - student or admin
- If admin then asks username and password
- If student then asks roll number and password

Then each one will have the options accessible as mentioned earlier
