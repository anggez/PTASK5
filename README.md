
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pt5</title>
    <style>
        body {
            background-image: url(https://img.freepik.com/premium-photo/abstract-pastel-colors-background-pink-blue-light-wrinkled-fabric_642878-146.jpg);
            background-repeat: no-repeat;
            background-size: 100%;
            margin: 1%;
            text-align: center;
        }
        h1 {
            font-size: xx-large;
        }
        form {
            margin: 0 auto;
            color: black;
            border-radius:  20px;
            border: solid;
            box-shadow: 5px 15px 15px rgb(103, 27, 110);
            width: 35%;
            padding: 20px;
        }
        input {
            font-size: 25px;
            padding: 5px;
            height: 15px;
            border-radius: 10px 10px 10px;
            border: solid rgb(211, 60, 216);
        }
        label{
            justify-content: center;
            align-items: center;
            font-size: 25px;
            display: block;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>BASIC FORM</h1>
    <h2>Angeline Estoperes</h2>
    <section>
        <form>
            <center>
                <label for="firstname">First Name:</label>
                <input type="text" id="firstname" name="firstname">

                <label for="middlename">Middle Name:</label>
                <input type="text" id="middlename" name="middlename">

                <label for="lastname">Last Name:</label>
                <input type="text" id="lastname" name="lastname">

                <label for="gender">Gender:</label>
                <input type="radio" id="male" name="gender">Male
                <input type="radio" id="female" name="gender">Female
                <input type="radio" id="other" name="gender">Other<br><br>

                <label for="transportation">How do you go to school?:</label>
                <input type="radio" id="Bus" name="transportation">Bus
                <input type="radio" id="commute" name="transportation">Commute
                <input type="radio" id="car" name="transportation">Car

                <label for="date">In what month were you born?:</label>
                <input type="date" id="birthday" name="birthdate">

                <label for="statement">Please say something about your self:</label>
                <input type="text" id="statement" name="statement">
                
                <button class="button-73" role="button">Submit</button>
            </center>
        </form>
    </section>
</body>
</html>
