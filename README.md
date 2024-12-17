# SkillSolutionsMagazine.github.io
A magazine for skill solutions academy fill with all training and services provided
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skill Solutions Magazine</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script src="turn.js-master/turn.min.js"></script>


    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }

        #flipbook {
            width: 700px;
            height: 460px;
            position: relative;
            z-index: 10;
        }

        #flipbook .page {
            width: 100%;
            height: 100%;
            background: white;
            border: 1px solid #ccc;
            text-align: center;
            line-height: 460px;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <div id="flipbook">
            <div>
                <img src="MAGAZINE.jpg" alt="Front Page" width="345" height="460" > 
            </div>    
            <div>
                <img src="MAGAZINE 2.jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE a.jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE (1).jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE (2).jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE b.png" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE (3).jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE c.png" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE (4).jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE (5).jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <div>
                <img src="MAGAZINE d.jpg" alt="Front Page" width="345" height="460" > 
            </div>
            <video width="400" controls>
                <source src="Clapping hand(sound effect).mp4" type="video/mp4">
                <source src="Clapping hand(sound effect)" type="video/ogg">
                Your browser does not support HTML video.
              </video>
              <div>
                <img src="MAGAZINE d.jpg" alt="Front Page" width="345" height="460" > 
            </div>
    </div>

    <button onclick="$('#flipbook').turn('previous')">Previous Page</button>
    <button onclick="$('#flipbook').turn('next')">Next Page</button>
    
    <script>
        $(document).ready(function () {
            $("#flipbook").turn({
                width: 700,
                height: 460,
                autoCenter: true,
                pages: 5
            });
        });
    </script>
</body>
</html>
