 insert into BORROWEDBOOKS values(4, 4, 4, TO_DATE('12-09-2024', 'DD-MM-YYYY'), TO_DATE('18-09-2024', 'DD-MM-YYYY'));
 
 SELECT * FROM MEMBERS;
 
 select * from borrowedbooks;
 
 select * from authors;
 
 select * from books;
 
 select name from authors where author_id=3;
 
alter table books add FOREIGN key(author_id) references authors(author_id);

UPDATE Members SET email = 'john.doe@gmail.com'WHERE member_id = 1;

SELECT * FROM Members;

SELECT title FROM Books WHERE author_id = 1;

SELECT COUNT(*) AS total_borrowed FROM BorrowedBooks;

UPDATE Books SET available_copies = available_copies - 1 WHERE book_id = 1;

INSERT INTO members values(5, 'Sarah Connor', 'sarah.connor@example.com');

SELECT m.name ,b.book_id FROM Members m  FULL OUTER JOIN BorrowedBooks b ON b.member_id= m.member_id;

DELETE FROM BorrowedBooks WHERE borrow_id = 4;

![conceptualdigram](https://github.com/user-attachments/assets/7fa18cc2-225d-4d72-8403-7e50f5a8d3ce)
![PL SQL](https://github.com/user-attachments/assets/594fd67a-69d6-4238-afcb-9e3ff5bad31a)

