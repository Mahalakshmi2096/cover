# Ex.06 Book Front Cover Page Design
## Date: 02/05/2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
book.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <link rel="stylesheet" href="bd styles.css">
</head>
<body>
    <div class="book-cover">
            <img src="C:\Users\MAHALAKSHMI B\Downloads\book cover.png" alt="bookcover" class="book-cover">
        <div class="content">
            <h1 class="title">The Journey Beyond</h1>
            <h2 class="subtitle">A Tale of Mystery and Adventure</h2>
        <div class="author-section">
                <img src="C:\Users\MAHALAKSHMI B\OneDrive\Documents\photo.jpg" alt="Author" class="author-image">
                <p class="author">by Mahalakshmi</p>
        </div>
        </div>
    </div>
</body>
</html>
bd styles.css
body {
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background-color: #f4f4f4;
    font-family: 'Arial', sans-serif;
}

.book-cover {
    position: relative;
    width: 750px;
    height: 750px;
    background-image: url("C:\Users\MAHALAKSHMI B\Downloads\book cover.png");
    background-size: cover;
    background-position: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    overflow: hidden;
}

.content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: white;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
    z-index: 2;
}

.title {
    font-size: 2em;
    margin: 0;
    text-decoration: black;
}

.subtitle {
    font-size: 1.2em;
    margin: 10px 0;
}

.author-section {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 20px;
}

.author-image {
    width: 100px;
    height: 100px;
    border-radius: 100%;
    border: 1px solid white;
    margin-bottom: 10px;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
}

.author {
    font-size: 1em;
    font-style: italic;
}
```
## OUTPUT:

![Screenshot 2025-05-02 223142](https://github.com/user-attachments/assets/98cc7a29-fa99-4a04-9f5e-c6f69e14c44b)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
