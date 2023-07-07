# Online-Food-Delivery-System
Design and implementation of online food delivery system which is user friendly, reliable and secured.

The application helps  in searching and sorting hotels and foods based on different categories and allows users to compare and choose.

Users can place food orders and track their delivery.

Application is built using standard sorting and searching algorithms.

# Functionalities

| SI. No |	Function Name |	Description	| DS and Algorithm Used |
|--------|----------------|-------------|-----------------------|
| 1.|	Start()	| Display zomato login page	||
|2.|	load()|	Display login and sign in page for user	||
|3.|	Login()|	Display  login  page for user. User have to enter correct username and password	||
|4.|	Signin()|	Display sign in page for user.	||
|5.|	Menu()|	Display available choices and takes input from the user	||
|6.|	Getnode()|	Dynamically allocates memory	malloc||
|7.|	Insert_hotel()|	Add hotel details from file to linked list|	Linked list|
|8.|	Insert_food()|	Add food details from file to linked list	|Linked list|
|9.|	Sort_foodprice()|	Sort the food list based on food price	|Selection sort|
|10.|	Sort_rating()|	Sort hotel list based on hotel rating	|Bubble sort|
|11.|	Bestseller()|	Find the food having highest rating and display it as bestseller of that hotel	||
|12.|	Search_hotel()|	Search entered hotel name is present or not|	Brute force string search|
|13.|	Order_food()|	Takes input from user what he want to order and finally print total amount to be paid	||
|14.|	Track_delivery()|	Finds shortest distance from the hotel to customer	|Adjacency matrix|
|15.|	Dijkstra()|	function to obtain minimum distance to all the points from the source point	|Priority queue|

# Function efficiency

| Function name |	Efficiency |
|---------------|------------|
|Login()|	constant|
|Signin()|	constant|
|All insert functions|	constant
|Display()|	N
|Sort_rating|	N2
|Sort_food|	N2
|Bestseller()|	N2
|Search_food()|	N2
|Search_hotel()|	mn
|Order_food()	|N2
|Takes_delivery()|	N2
