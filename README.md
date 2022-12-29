# classworks
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact us</title>
</head>
<style>
    .contact{
        padding: 10px;
    }
   
    .name{
        line-height: 3;
    }
    .email{
        line-height: 3;
    }
   
    .sub_ph{
        line-height: 3;
    }
 
</style>
<body>
    <div class="contact">
        <h1>Contact us</h1>
        <form action="backend.php">
            <div class="name">
            <label for="Name"></label>
            <input type="text" name="UserName" id="Name" placeholder="Full Name">
            </div>
            <div class="email">
            <label for="Email"></label>
            <input type="email" name="UserMail" id="Email" placeholder="Email">
            </div>
            <div class="sub_ph">
            <label for="Subject"></label>
            <input type="text" name="Query" id="Subject" placeholder="Subject">
            <label for="Phone"></label>
            <input type="tel" name="UserPhone" id="Phone" pattern="[0-9][10]" placeholder="Phone">
            </div>
            <textarea name="Message" id="" cols="30" rows="10" placeholder="Message"></textarea>
        </form>
    </div>
</body>
</html>
