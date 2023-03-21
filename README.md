<html>
  <head>
    <title>PinkPop - Your one-stop shop for all things pink!</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      /* Global Styles */
      body {
        background-color: pink;
        font-family: Arial, sans-serif;
        font-size: 16px;
        line-height: 1.5;
        color: #444;
      }
      
      /* Header */
      header {
        background-color: white;
        padding: 10px 20px;
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      
      header img {
        max-height: 50px;
      }
      
      header nav {
        display: flex;
      }
      
      header nav ul {
        list-style: none;
        margin: 0;
        padding: 0;
        display: flex;
      }
      
      header nav ul li {
        margin-left: 20px;
      }
      
      header nav ul li a {
        text-decoration: none;
        color: #444;
        padding: 10px;
        border-radius: 5px;
        transition: background-color 0.2s ease;
      }
      
      header nav ul li a:hover {
        background-color: #f4f4f4;
      }
      
      /* Main Content */
      main {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        margin: 20px;
      }
      
      .product {
        background-color: white;
        box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
        border-radius: 5px;
        width: calc(33.33% - 10px);
        margin-bottom: 20px;
        overflow: hidden;
      }
      
      .product img {
        width: 100%;
        height: 200px;
        object-fit: cover;
      }
      
      .product h2 {
        font-size: 20px;
        margin: 10px;
      }
      
      .product p {
        font-size: 16px;
        margin: 10px;
      }
      
      .product button {
        display: block;
        margin: 10px;
        padding: 10px;
        background-color: #ff69b4;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.2s ease;
      }
      
      .product button:hover {
        background-color: #ff8cc6;
      }
      
      /* Footer */
      footer {
        background-color: white;
        padding: 20px;
        text-align: center;
        font-size: 14px;
      }
      
    </style>
  </head>
  <body>
    <header>
      <img src="https://via.placeholder.com/150x50" alt="PinkPop Logo">
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Shop</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav
