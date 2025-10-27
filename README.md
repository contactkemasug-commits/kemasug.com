/* Reset simple */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background-color: #1f1f1f;
}

.logo {
    width: 120px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

.banner {
    text-align: center;
    padding: 60px 20px;
    background-color: #2c2c2c;
}

.banner h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

.banner p {
    font-size: 1.2em;
}

.content {
    padding: 40px 20px;
}

.content h2 {
    margin-bottom: 20px;
}

.cards {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background-color: #1f1f1f;
    padding: 10px;
    border-radius: 8px;
    width: 200px;
    text-align: center;
}

.card img {
    width: 100%;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #1f1f1f;
    margin-top: 40px;
}
