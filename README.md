<h1>Food Delivery Service Prototype</h1>

 ### [Video Demonstration](https://youtu.be/2HvzjrypxU4)

<h2>Description</h2>
Our food delivery service product will offer a grocery delivery service that combines  
the best interests of consumers, employees, and store owners alike. The product will
allow consumers to select products from a store’s inventory to add to an order, and 
place said orders using a chosen address and payment method to be carried out by 
employees. The manager of each store that uses our product will also interact with 
the application to ensure that products can be ordered and delivered as efficiently as 
possible. With this product, we hope to provide a simple yet effective service for 
virtual grocery shopping that surpasses the many shortcomings of existing services.
Consumers should be able to easily interact with the application, employees should
be able to easily carry out orders and manage the money they earn from doing so, 
and store managers should be easily able to adjust their store’s online inventory.
</br>
</br>
The product's current implementation contains routes for the consumer persona that
currently allow us to get info of all customers from the database ('get'), get info of a 
particular customer ('get'), view all reviews that have been left ('get'), and enable 
customers to leave a review of an order ('post'). For the employee persona, the current 
routes allow us to access a certain employee from the database ('get'), get all existing 
payments ('get'), and get all transactions involving a certain employee ('get'), in hopes
of implementing bank account transfer capabilities in the future. The routes for a store 
manager allow access to all store managers from within the database ('get'), allow the 
ability to apply a new store and store manager ('post'), and allow a store manager to update 
their store's inventory ('post'). Finally, we are also able to access all stores from the 
database ('get'), their names ('get'), as well as all the products within a certain store 
('get'). 

<h2>How to setup and start the containers</h2>
<b>Important - you need Docker Desktop installed</b>

1. Clone this repository.  
2. Create a file named `db_root_password.txt` in the `secrets/` folder and put inside of it the root password for MySQL. 
3. Create a file named `db_password.txt` in the `secrets/` folder and put inside of it the password you want to use for the `webapp` user. 
4. In a terminal or command prompt, navigate to the folder with the `docker-compose.yml` file.  
5. Build the images with `docker compose build`
6. Start the containers with `docker compose up`.  To run in detached mode, run `docker compose up -d`.

<h2>Languages and Utilities Used</h2>

- <b>Python</b>
- <b>SQL</b>
- <b>Flask</b>

<h2>Environments Used</h2>

- <b>Pycharm CE</b>
- <b>DataGrip</b>
- <b>Appsmith (front-end connection)</b>

<h2>Program walk-through:</h2>

<p align="center">
View of stores: <br/>
<img width="956" alt="image" src="https://user-images.githubusercontent.com/113547817/207407411-ff5cc3e0-6a9b-4dc2-847c-0e14bf1491af.png">
<br />
<br />
View of reviews:  <br/>
<img width="949" alt="image" src="https://user-images.githubusercontent.com/113547817/207407528-0782de5b-96e2-4402-a338-b4f562175061.png">
<br />
<br />
View of employee payments:  <br/>
<img width="943" alt="image" src="https://user-images.githubusercontent.com/113547817/207407756-7a882c43-c833-4f91-881a-641e9b3efee4.png">
<br />
<br />
View of partnership application: <br/>
<img width="944" alt="image" src="https://user-images.githubusercontent.com/113547817/207407869-5c0067a0-848c-4a06-86dc-cd72372836e4.png">
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
