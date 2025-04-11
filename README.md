#страница1
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f9
    color: #333;
    line-height: 1.6;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

h1 {
    font-size: 3rem;
    text-align: center;
    color: #2c3e50;
    letter-spacing: 2px;
    text-transform: uppercase;
    animation: fadeIn 2s ease-in-out;
}

.container {
    text-align: center;
    padding: 20px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 80%;
    max-width: 600px;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

h1:hover {
    color: #e74c3c;
    cursor: pointer;
    transition: color 0.3s ease-in-out;
}

#страница2

* {
    box-sizing: border-box;
}
:root {
    --background-color: black;
    --text-color: hsl(0, 0%, 100%);
}
body {
    margin: 0;
}
.wrapper {
    display: grid;
    place-content: center;
    background-color: var(--background-color);
    min-height: 100vh;
    font-family: "Oswald", sans-serif;
    font-size: clamp(1.5rem, 1rem + 18vw, 15rem);
    font-weight: 700;
    text-transform: uppercase;
    color: var(--text-color);
}
.wrapper > div {
    grid-area: 1/1/-1/-1;

}
 .top {
clip-path: polygon(0% 0%, 100% 0%, 100% 48%, 0% 58%);
}
.bottom {
clip-path: polygon(0% 60%, 100% 50%, 100% 100%, 0% 100%);
color: transparent;
background: -webkit-linear-gradient(177deg, black 53%, var(--text-color) 65%);
background: linear-gradient(177deg, black 53%, var(--text-color) 65%);
background-clip: text;
-webkit-background-clip: text;
transform: translateX(-0.02em);
}
