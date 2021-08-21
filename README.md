# PhoneBook-application

## Description
As mentioned above many times, this phonebook application can perform each and every 
operation that a phonebook should perform. From adding a particular to deleting and 
modifying it,we can perform everything in it. There are many ways In which this 
application can be executed , but here in our program we have mainly focused on “singly 
linked list”. Now there might be a question that why we are using this particular data 
structure in our project while we have easy to handle things like array. So the basic answer 
to this question is that we need to made this project in a way so that it can’t be just kept 
somewhere in a corner ,but to make it available for each and everyone . And it could only be 
possible when it would solve the problem or defaults in the previous programs. Our main 
thing while making this program was to reduce its space and time complexity. That is the 
reason we used linked list data structure instead of array.
The list of operations that can we perform in our data structure is as follows:
#### 1) Adding contacts:

As the name suggests, this part help us to add contact in our contact list. Here user will be 
asked to enter his/her name ,contact number,gender ,mail –Id etc. ,and all the details will get 
saved in our list. Basically our list is nothing more than a singly linked list ,where each 
contact is acting as a node and things like name, mail are like the fields for that particular 
node. And what we are doing is we are just connecting all those node to fill our list.
#### 2) Deleting the contact:

Deleting the contact means just removing the contact from our contact list or so called 
linked list. As mentioned earlier each contact is a node so actually we are just removing a 
node from our linked list. And also it dosen’t matter that what is the position of the contact 
that iss to be removed it can remove contact from any position ,successfully.
#### 3) Searching the contact:

Suppose as user you added 700-800 contacts in your list.So imagine what the situation 
would be if you want to search number for someone. Practically it would be like finding a 
number from city’s directory ,in that case of what use our phonebook application would be? 
This is the main reason for creating this function and it is very different from normal search 
function you need not to write whole name of contact to search fpr his name only ypu can 
use the initals of name for searching ,so this make it unique and easy to use.Basic idea 
behind this is traversing the linked list.
#### 4) Modifying the contact details:

In the case if you get someone’s name wrong then this function enables you to change not 
only the name of the person but each and every detail of that person ,including gender also. 
So if mistakenly we add some wrong details then there is no need to worry as we can 
change them .We will do this using traversing the linked list till that particular point.
#### 5) Displaying all the contacts:

This function helps you to see each and every contact in your list at the same time.You just 
need to select this option and and it will show all the contacts you had saved till now 
including their details. Here we will be using traversing and sort of swapping things. The 
contacts can be easily displayed by just entering one or two letters of the name or two three 
numbers of the respective contact.
### OUTPUT:

Here using add contacts function we have added three contacts of our dear friends 
,for now, namely, Samyak, Agasthya, Jasshu. After this we will show all the 
contacts which are saved ,this is as follows:
