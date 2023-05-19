## Object-Relational Mapping (ORM) Challenge: E-commerce Back End


## 1. Description

This application is a backend application servicing front end routes and using MySQL database with Node and Express. 

### Snapshot

![tech](./assets/images/code-used.JPG?raw=true "code-used.JPG")

<a name="web-address"></a>
## 2. How to Get There

### Open your favorite web browser and enter the following web address to access to the README.md

https://github.com/MackOyler/E-Commerce.Back-End

<a name="usage"></a>
## 3. Usage Tips

For more information - Please visit the following videos on how the application works and some background information on the app build.

If you want to run locally preform the following:

This application is running under mysql as a local host, you can modify the .env file with your own user/password to start the application.

If you are still intersted in running the application you would need to do the following:
* run mysql terminal at project source location
  source db/schema.sql
* npm i
* npm run seed
* npm start
* use Insomnia (use videos and sample snapshots using Insomnia for Product model for your reference).


## 4. Features

### GET (Select All), GET by id (Select by ID), POST (Create), PUT (Update), DELETE (Destroy)

 *** Functionality of one route as example: *** 

### GET all products.

![step](./assets/images/insomnia_get_all_products.JPG?raw=true "insomnia_get_all_products.JPG")

### GET product by ID.

![step](./assets/images/insomnia_get_all_products_by_id.JPG?raw=true "insomnia_get_all_products_by_id.JPG")

### POST/Create product.

![step](./assets/images/insomnia_post_create_product.JPG?raw=true "insomnia_post_create_product.JPG")

### PUT/Update product by ID.

![step](./assets/images/insomnia_put_update.JPG?raw=true "insomnia_put_update.JPG")

### GET product by ID after update.

![step](./assets/images/insomnia_get_all_products_by_id_updated.JPG?raw=true "insomnia_get_all_products_by_id_updated.JPG")

### DELETE product by ID.

![step](./assets/images/insomnia_delete_by_id.JPG?raw=true "insomnia_delete_by_id.JPG")

### GET product after delete not found.

![step](./assets/images/insomnia_get_all_products_by_id_notfound.JPG?raw=true "insomnia_get_all_products_by_id_notfound.JPG")



<a name="credits"></a>

## 5. Contributor 
[Mack Oyler][https://github.com/MackOyler]
