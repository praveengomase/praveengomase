<!DOC TYPE html>
<html>
    <head>
        <style>
            body{
                background-color: lightblue ;
                text-align: justify;
                font-style: normal;
                font-family: Verdana, Geneva, Tahoma, sans-serif;
            }
            h1{
                font: 200px;
                font-style: bold;
            }
        </style>
        <meta charset="UTF-8">
        <title>LOGIN</title>
    </head>
    <body>
        <form>
        <h1>Signup</h1>
        <div>
            Full Name:<br>
            <input type="text" name="full-name">
        </div>

        <div>
            Email:<br>
            <input type="Email" name="Email">
        </div>
        <div>
            password:<br>
            <input type="password" name="password">
        </div>
        <div>
            confirm password:<br>
            <input type="password" name="confirm-password">
        </div>
        <div>
            Gender:<br>
            <input type="radio" name="male" value="male" > Male </input>
            <input type="radio" name="female" value="female" > Female</input>
            <input type="radio" name="other" value="other" >Other</input>
        </div>
        <div>
            Security Question:<br>
            <select name="security-question">
                <option value="what was your first pet name"> what was your first pet Name </option>
                <option value="who is your favorite crickter"> who is your favorite crickter</option>
                <option value="what is your nick-name"> what is your nick-name</option>
            </select>
        </div>
        <textarea name="answer" rows="8"
        cols="35"></textarea>
        <div>
            <input type="checkbox" name="terms and conditions" value="accept"> I agree to accept terms and conditions
        </div><br>
        <input type="submit" value="Register">
        </form>
    </body>
</html>
