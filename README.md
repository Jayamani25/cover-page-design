# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github repository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for designing book cover page and execute them.

## Code:
```Html
<!DOCTYPE html>
<html>
<head>
  <title>Cloud Computing Book Cover</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .container {
      width: 400px;
      height: 500px;
      margin: 50px auto;
      padding: 20px;
      background-color:white;
      background-position: center;
      background-image: url(/static/html/cloud1.jpg);
      border: 1px solid #ccc;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    h1 {
      text-align: center;
      color:skyblue;
      font-size: 30px;
      font-style: bold;
      margin-top: 200px;
    }
   
    .book-title {
      text-align: right;
      color:orange;
      font-style: italic;
      font-size: 18px;
      margin-top: 150px;
    }
    .author {
      text-align:right;
      color: grey;
      font-style: italic;
      font-size: 20px;
      margin-top:auto;
    }
  </style>
</head>
<body >

  <div class="container">
    <h1>WAY TO CLOUD COMPUTING</h1>
    <h2 class="book-title">Edition 1<br>
        ------------------------------------------------------------------</h2>
    <p class="author">Jayamani.R</p>
    
  </div>
</body>
</html>
```

## Output:
![Screenshot (15)](https://github.com/Jayamani25/cover-page-design/assets/85949888/9c02f84f-c1aa-4e54-8d42-f874b5c8c4c6)


## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
