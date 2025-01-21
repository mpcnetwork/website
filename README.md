<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loading effect</title>
</head>
<style>
    html {
    height: 100vh;
}

body {
    height: 100%;
    display: flex;
    font-family: "mono", monospace;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background: #253238
}

h1 {
    position: relative;
    font-size: 50px;
    text-transform: uppercase;
    color: #212121;
    border-bottom: 10px solid #212121;
}

h1:before {
    top: 0;
    left: 0;
    content: 'MPCNetwork';
    color: #00ffff;
    position: absolute; 
    overflow: hidden;
    border-bottom: 10px solid #00ffff;
    animation: loading 8s infinite linear;
}

@keyframes loading {
    0% {
        width: 0;
    }
    100% {
        width: 100%; 
    }
}
</style>
<body>
    <h1>MPCNetwork</h1>
</body>
</html>

<!-- ![ondrr constructie](https://github.com/user-attachments/assets/c01ae0b3-b85c-4576-b10f-a413e31cc2c9)

Goedemorgen! Hier is de afbeelding die het concept van "Constructie" toont 
Met machinekraan bedieners die het woord "onder" nog aan het liften zijn om bovenop "constructie" te plaatsen:
                                                                                                            😊🚧🏗️
mpcnetwork --!>
