<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation</title>
    <style>
        @keyframes spinRotate {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }

        img {
            width: 256px;
            height: 256px;
            animation-name: spinRotate;
            animation-duration: 5s;
            animation-iteration-count: infinite;
            animation-timing-function: ease-in-out;
        }

        div {
            display: flex;
            justify-content: center;
            align-items: center;
            /* border: 1px solid; */
            width: 100%;
            height: 100vh;
        }
    </style>
</head>

<body>
    <div>
        <img src="https://cdn.pixabay.com/photo/2014/04/03/00/35/gear-wheel-308798_960_720.png">
    </div>
</body>

</html>
