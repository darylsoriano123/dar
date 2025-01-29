<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
</head>

    <?php
        $name = "Daryl Dean Soriano";
        $number = "09927427172";
        $email = "darsoriano@gmail.com";
        $address = "San Miguel, Jordan, Guimaras";
        $summary = " Efficient and Friendly encoder with 1 year of work experience operating in 
                    NASA Defense System and 1 year of work experience in Space X helping to 
                    lunch the Starship.";
        $summary1 = "Manually operating in with the guidance of my seniors in
                     NASA Defense System. 1 month non-stop looking for 
                     UAP that enter out planet.";
        $summary2 = "Operating in Space X helping to 
                    lunch the Starship. With the help of Elon Musk we achieve to lunch successfully.";
        $school = "TVC Sta. Teresa National Highschool";
        $hub1 = "Playing Video Games ";
        $hub2 = "Trail Enduro";
        $hub3 = "Shooting Stars";
        $hub4 = "Watching ASMR";
        $hub5 = "Coding";
    ?>

    <!-- HEADER -->
    <header>
        <img src="pic.png" alt="" width="127px"style="margin-left: 25%;">
        <table>
            <tr>
                <td>
                    <h1><?php echo$name; ?></h1>
                </td>
            </tr>
        </table>
    </header>


    <!-- PERSONAL DETAILS -->
        <h2>Personal Details</h2>
        <hr>
        <table border="2px ">

            <tr>
                <td><h3>Name</h3></td>
                <td><p><?php echo$name;?></p></td>
            </tr>

            <tr>
                <td><h3>Phone Number</h3></td>
                <td><p><?php echo$number;?></p></td>
            </tr>
            
            <tr>
                <td><h3>Email Address</h3></td>
                <td><p><?php echo$email;?></p></td>
            </tr>
            <tr>
                <td><h3>Address</h3></td>
                <td><p><?php echo$address;?></p></td>
            </tr>
        </table>
        <br>

    <!-- SUMMARY -->
     <h2>Summary</h2>
     <hr>
         <p><?php echo$summary?></p>
     <br>

    <!-- WORK EXPERIENCE -->
    <h2>Work Experience</h2>
    <hr>
    <table border="2px ">
        <tr>
            <td><strong>Dec. 12 2021</strong></td>
            <td><p><?php echo$summary1;?></p></td>
        </tr> 
        <tr>
            <td><strong>Jan. 11 2023</strong></td>
        <td><p><?php echo$summary2;?></p></td>
        </tr>
    </table>
    <br> 

    <br>   
    <!-- EDUCATION -->
    <h2>Education</h2>
    <hr>
    <table border="2px">
        <tr>
            <td>
                <strong>2017-2019</strong>
            </td>
            <td>
                <p><?php echo$school;?></p>
            </td>
        </tr>
    </table>
    <br>

    <!-- HOBBIES -->
    <h2>Hobbies</h2>
    <hr>
    <table>
        <tr>
            <td>
                <ul>
                    <li><?php echo$hub1;?></li>
                    <li><?php echo$hub2;?></li>
                    <li><?php echo$hub3;?></li>
                    <li><?php echo$hub4;?></li>
                    <li><?php echo$hub5;?></li>
                </ul>
            </td>
        </tr>
    </table>

</body>
</html>
