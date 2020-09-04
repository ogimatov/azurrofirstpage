<?php
include_once 'azurroheader.php'
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="azurrostyle.css" media="screen"/>
    <title>Index1</title>
</head>
<body>
    <div class="main">
        <div class="text">
            <h3>Private site for Azurro Garden owners.</h3>
            <h3>......................................</h3>
        </div>
        <form action="azurrodb.php" method="POST">

            <label for="fname">Name of owner:</label><br>
            <input type="text" id="fullname" name="fullname" placeholder="Enter your name.."><br>

            <label for="apartnumber">Number of apartment:</label><br>
            <input type="text" id="apartnumber" name="apartnumber" placeholder="Enter your apartment number.."><br><br>

            <label for="garagenumber">Number of garage:</label><br>
            <input type="text" id="garagenumber" name="garagenumber" placeholder="Enter your garage number .."><br><br>

            
            <input type="submit" id="submitbuton" value="Submit"><br><br>
        </form>
    </div>
</body>
<?php
include_once 'azurrofooter.php';
?>
</html>
