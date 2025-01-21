# Kodland HTML5-CSS Project

This project is a simple HTML5 and CSS application designed to showcase basic styling principles and responsive design. It uses a Google Font (`Inter`) and a custom color scheme to create a visually appealing layout.

---

## Project Structure

Make sure your project is organized as follows:

project/ │ ├── templates/ │ └── index.html │ ├── static/ │ └── style.css │ └── images/ │ └── image.png


### Files Overview:
- **`templates/index.html`**: The main HTML file containing the structure of the webpage.
- **`static/style.css`**: The CSS file defining the visual styling of the page.
- **`static/images/image.png`**: A sample image included for demonstration.

---

##  Features

### Font
- Font used: **Inter**  
  (Loaded via Google Fonts: [https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap](https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap))

### Colors
The color scheme includes:
1. **Blue**: `#5988FF`
2. **Pink**: `#FD98FB`
3. **Green**: `#D6FF6B`
4. **White**: `#FFFFFF`

---

## 📄 How to Use

### 1. Setting Up the Project

1. Create the folder structure as shown above (`templates` and `static` folders).
2. Add the respective files in the correct directories:
   - **`templates/index.html`**: Contains the HTML structure.
   - **`static/style.css`**: Contains the CSS styles.
   - **`static/images/image.png`**: Contains the image used in the project.

### 2. Add Code to Files

- **`templates/index.html`**
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Kodland HTML5-CSS Project</title>
        <link rel="stylesheet" href="../static/style.css">
        <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    </head>
    <body>
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5>
        <h6>Heading 6</h6>
        <p>This is an example paragraph.</p>
        <ul>
            <li>Option 1</li>
            <li>Option 2</li>
        </ul>
        <img src="../static/images/image.png" alt="Sample Image">
    </body>
    </html>
    ```

- **`static/style.css`**
    ```css
    body {
        font-family: 'Inter', sans-serif;
        background-color: #5988FF;
        color: #FFFFFF;
        margin: 0;
        padding: 0;
        text-align: center;
    }

    h1 {
        color: #FD98FB;
        font-size: 2.5em;
        text-decoration-color: #D6FF6B;
    }

    h2 {
        color: #D6FF6B;
        font-size: 2em;
    }

    h3 {
        color: #FD98FB;
        font-size: 1.8em;
    }

    h4, h5, h6 {
        color: #FFFFFF;
    }

    p {
        font-size: 1.2em;
        line-height: 1.6;
        padding: 10px;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    img {
        max-width: 100%;
        height: auto;
    }
    ```

---

### 3. Preview the Project with Live Server

To open the project in your browser using **Live Server**:

1. Install the **Live Server** extension in Visual Studio Code.
2. Right-click on `index.html` (inside the `templates` folder) and select **"Open with Live Server"**.
3. The project will open in your default web browser, and any changes you make will update in real-time.

---


