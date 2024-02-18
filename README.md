<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="content">
            <h2>First Heading</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec euismod, nisl eget molestie consectetur, ipsum justo laoreet odio, quis tincidunt ante sapien vel orci. Donec euismod, nisl eget molestie consectetur, ipsum justo laoreet odio, quis tincidunt ante sapien vel orci.</p>
            <h3>Subheading</h3>
            <p>Curabitur aliquam lorem eget ligula ullamcorper malesuada. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Praesent blandit leo vel magna.</p>
        </section>
        <section class="content">
            <h2>Second Heading</h2>
            <p>Suspendisse potenti. Sed posuere consectetur est at lobortis. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Donec posuere vulputate elit.</p>
            <h3>Subheading</h3>
            <p>Nulla vitae elit libero, a pharetra augue. Donec id elit non mi porta gravida at eget metus. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>
        </section>
        <section class="content">
            <h2>Third Heading</h2>
            <p>Curabitur blandit tempus porttitor. Donec id elit non mi porta gravida at eget metus. Nullam quis risus eget urna mollis ornare vel eu leo.</p>
            <h3>Subheading</h3>
            <p>Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Donec id elit non mi porta gravida at eget metus. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Website</p>
    </footer>
</body>
</html>

body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f1f1f1;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 24px;
    margin: 0;
}

nav {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #333;
}

nav a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
}

.content {
    margin-bottom: 20px;
}

h2 {
    font-size: 20px;
    margin-bottom: 10px;
}

h3 {
    font-size: 16px;
    margin-bottom: 5px;
}

p {
    line-height: 1.5;
}

footer {
    background-color: #f1f1f1;
    text-align: center;
    padding: 10px;
}
