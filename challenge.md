# Challenge begin

## 1:
  Create a simple program asking for password and compare 
  the input with password,if password is correct congrat 
  for sucessfull login else yell incorrect password 

## 2:
  Create a simple more secure program asking for password
  and encrypt input with your own algorithm and compare with
  encrypted real password.if password match congrat 
  for sucessfull login else yell incorrect password.

### Hints:
     Its about your algorithm topic.Many secure login use
     its own algirithm.But we are not expert so you can
     implement your own algorithm for encryption.
     For example:

  1. You can add ascii value of string and compare with password ascii value sum.
  2. You can rearrange the letter of string and make another string like hash and
    compare it with password hash like if 'a' is present then a became 'd',if 'd'
    then 'x'any letter randomly.

## 3:
    Create a simple more secure program asking for password
    and encrypt input with your own algorithm and compare with
    encrypted real password.if password match congrat for 
    sucessfull login else yell incorrect password.But at this time
    encrypted password is stored in a file and you have to read from
    file and check password.If there is no file yell program is corrupted.  
### Hints:
      It seems that way of authentication in point 1 of challenge
      2 is less secure than number 2.It is not full proof secure
      but more secure than that one.Lets make it more secure.
      Take hash of string and at one third place of hash add a
      special letter that letter can be same or different.

      For Example:
      If hash is "AX83VE" then "AX" + "@" + "83" + "@" + "VE"
      In place of "@" you can use any letter or may be different
      letter at different position.

## 4:
    Create a simple menu based calculator which first ask for first
    number,secondly operator and lastly second number.If operator
    is not appropriate yell unappropriate operation otherwise perform
    operation and give the result to the user.

## 5:
   Create a simple menu based password manager with security.
### Hints:
    Take the authentication program from challenge 3 with menu
    based system mentioning:
  - Create new Entry
  - Delete Entry
  - Show Entry
   And manage your gmail,facebook,etc password in file.Yeah it is not
   secure to store without encryption but later we will.


## 6:
  Create a simple library management system.
### Hints:
   Ask for login.As a super user make your password for simple
   user
   Username:admin 
   Password:admin 
   And super user create,Edit and delete book entry.You can use
   struct with file handling.
   As for simple user can only look all entry or search by id number.
   Again use same struct which is use to write at file and read from
   file and show.
  

## 7:
  Create a function which convert string into number like "123" into
  123 and print for testing.  

## 8:
  Create a function which convert number into string like 123 into
  "123" and print for testing.

## 9:
  Create a function which convert number into string represented
  as hex like if number is 123 then into "7B".And print for testing.

## 10:
  Create a simple readline function which read all the input untill
  enter is pressed or an error occured.
### Hints:
   Since C doesnot check overflow of buffer,using scanf if we
   type more character than expected then there occur bufferoverflow
   which can corrupt or even crash your program so with the help
   of dynamical allocating function malloc and fgetc we can implement
   readline function to prevent bufferoverflow.But dont forget to
   free that allocated memory.

