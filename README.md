# Google Logo
The Google Logo project is a visually appealing representation of the iconic Google logo using HTML and CSS. The code creates a stylized logo with vibrant colors and a unique shape, showcasing the familiar four-color scheme associated with Google. This simple and creative implementation is suitable for learning purposes or as a starting point for more complex web design projects. Explore and modify the code to customize the logo to fit your preferences or integrate it into your web development endeavors.

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Logo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="google-logo"></div>
</body>
</html>
```

## CSS
```css
body {
    padding: 0;
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: azure;
}

.google-logo {
    position: relative;
    width: 300px;
    height: 300px;
    padding: 0;
    border-top: 100px solid #ea4335;
    border-right: 100px solid #4285f4;
    border-bottom: 100px solid #34a853;
    border-left: 100px solid #fbbc05;
    border-radius: 50%;
    background-color: azure;
}

.google-logo::before {
    content: "";
    position: absolute;
    top: 50%;
    right: -95px;
    transform: translateY(-50%);
    width: 230px;
    height: 100px;
    background-color: #4285f4;
}

.google-logo::after {
    content: "";
    position: absolute;
    top: -100px;
    right: -100px;
    width: 0;
    height: 0;
    border-top: 200px solid transparent;
    border-right: 200px solid azure;
}
```

Feel free to use and modify this code for your projects.
