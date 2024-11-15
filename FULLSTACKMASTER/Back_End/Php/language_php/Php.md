1.Php variables: Biến PHP
<!-- When you assign a text value to a variable, put quotes around the value.
    --Khi bạn gán một giá trị dạng văn bản cho một biến, hãy đặt dấu ngoặc kép xung quanh giá trị đó--
Unlike other programming languages, PHP has no command for declaring a variable. It is created the moment you first assign a value to it. 
--Không giống như các ngôn ngữ lập trình khác, PHP không có lệnh để khai báo một biến. Biến được tạo ra ngay khi bạn gán giá trị cho nó lần đầu tiên--
-->


<!-- In PHP, variables can be declared anywhere in the script.
    --Trong PHP, biến có thể được khai báo ở bất kỳ đâu trong tập lệnh.--
    The scope of a variable is the part of the script where the variable can be referenced/used.
    --Phạm vi của một biến là phần của tập lệnh nơi biến đó có thể được tham chiếu hoặc sử dụng.--
    PHP has three different variable scopes:
        Cục bộ (local)
        Toàn cục (global)
        Tĩnh (static)
-->

2.PHP Data Types
<!-- 
Variables can store data of different types, and different data types can do different things.

PHP supports the following data types:

String
Integer
Float (floating point numbers - also called double)
Boolean
Array
Object
NULL
Resource

-->

3.PHP String
<!-- Strings in PHP are surrounded by either double quotation marks, or single quotation marks.('',"")

    The PHP strlen() function returns the length of a string.                                                   <strlen()>     

    The PHP str_word_count() function counts the number of words in a string.                                   <str_word_count()>

    The PHP strpos() function searches for a specific text within a string.                                     <strpos()>

    The strtoupper() function returns the string in upper case                                                  <strtoupper()>

    The strtolower() function returns the string in lower case                                                  <strtolower()>

    The PHP str_replace() function replaces some characters with some other characters in a string.             <str_replace(find, replace, string)>
    
    The PHP strrev() function reverses a string                                                                 <strrev()>

    Whitespace is the space before and/or after the actual text, and very often you want to remove this space.  
    The trim() removes any whitespace from the beginning or the end:                                            <trim()>

    The PHP explode() function splits a string into an array.
       Hàm explode() trong PHP chia một chuỗi thành một mảng.
    The first parameter of the explode() function represents the "separator".
    The "separator" specifies where to split the string.
       Hàm explode() trong PHP chia một chuỗi thành một mảng.                                                  <explode(separator, string, limit)>                       
 -->
