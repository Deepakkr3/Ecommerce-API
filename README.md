# <h1 align = "center"> Ecommerce_Api_USing_Mapping Spring_Boot &mySql</h1>

---

<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->

## Overview

<p align="center">This project, named "User Management System," is a robust Spring Boot application designed for managing user data efficiently. It provides a set of API endpoints that allow you to perform various operations on user records, such as adding, retrieving, updating, and deleting user information. 
</p>

<!-- Table of Contents -->

## Table of Contents

1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->

## Technologies Used

- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- JPA
- Lombok
- mySql

<!-- Key Features -->

## Mapping

-One to One

## Key Features

Steps:1. Create users 2. Create products 3. Create Address 4. Place an order (Create Order) using userId, productId, addressId

5. Get order by order id
6. Get user by userid
7. Get all products

- Get products based on category (query params)

8. delete products based on product id.

<!-- Usage -->

## Usage

- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to manage your User Management.

### Controller:

- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.

### API Reference

### Address Controller

    @PostMapping("post/addres")

### Order Controller

         @PostMapping("post/order")

         @GetMapping("oderBy/Id/{id}")

### Product Controller

         @PostMapping("post/product")

         @GetMapping("products")

         @GetMapping("product/category")

        @DeleteMapping("delete/product")

### User Controller

       @PostMapping("post/user")

       @GetMapping("user/Id/{id}")

 <!-- Acknowledgments -->

## Acknowledgments

- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->

## Contact

For questions or feedback, please contact : Deepak kumar singh -

- Maild Id : deepakbaitha7905@gmail.com

<h1 align="center">Thank You...<h1>
<h3 align = "center"> ***********************************************************<h3>
