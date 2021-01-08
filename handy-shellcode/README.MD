Bài này thực sự rất dễ.
Mình chỉ cần đưa shellcode để nó chạy, Nhưng vì nó ngăn chặn tham số "/bin/sh" nên chúng ta sẽ tìm shellcode phù hợp.
Ở đây mình lấy 1 shellcode: setuid(0) và sao đó là shell "/bin/sh" 
Vì sao phải dùng setuid(0), vì chương trình đã setuid ngăn không cho mình thực thi "/bin/sh" nên chúng ta sẽ cho nó về giá trị mặc định.