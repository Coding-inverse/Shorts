<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Button_(V.0.0.5)</title>
    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background: #e3e3e3;
}

/* CSS */
button {
    position: relative;
    font-weight: 600;
    height: 40px;
    padding: 12px 20px;
    outline: none;
    border: 1px solid black;
    background-color: transparent;
    border-radius: 5px;
}

button:after {
    content: "";
    position: absolute;
    width: 100%;
    top: 7px;
    left: 7px;
    height: 100%;
    background-color: rgb(201, 184, 246);
    z-index: -1;
    transition: all 0.35s;
    border-radius: inherit;
}

button:hover:after {
    top: 0px;
    left: 0px;
}
    </style>
</head>
<body>
    <!-- HTML  -->
    <button>Hover me</button>
</body>
</html>
