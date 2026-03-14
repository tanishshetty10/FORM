<!DOCTYPE html>
<html>
 <head>
    <title>my g</title>
 </head>


<body bgcolor="#256368">

    <form action="post">
        <h1>HI THIS IS YOUR APPLICATION</h1>

        <br>
        <hr color="#000000" size="5px" width="100%">
        <br>
<div>
<label for="fname">first name:</label>
<input type="text" id="fname" name="fname" placeholder="tan" required>
</div>

<br>
<div>

<label for="lname">last name:</label>
<input type="text" id="lname" name="lname" placeholder="lala"required>

</div>

<br>

<div>
<label for="pass">password:</label>
<input type="password>" id="pass" name="pass" maxlength="12" required>
</div>

<br>
<div>
<label for="email">email:</label>
<input type="email" id="email" name="email">

</div>

<br>
<div>
<label for="bdate">birthdate</label>
<input type="date" id="date" name="date">

<br>
</div>

<br>
<div>
<label for="quantity">quantity</label>
<input type="number" id="quantity" name="quantity" min="0" max="10" value="1">

</div>
<br>

<div>
<label for="title">title:</label>

<label for="mr.">mr.</label>
<input type="radio" id="mr." name="title" value="mr.">


<label for="mrs.">mrs.</label>
<input type="radio"id="mrs." name="title" value="mrs.">

<label for="none.">none.</label>
<input type="radio"id="none." name="title" value="none.">

</div>
<br>

<div>
<label for="payment">payment</label>
<select id="payment" name="payment">

<option value="no money">no money</option>
<option value="free money">free money</option>
<option value="ok money">ok money</option>
<option value="yaya money">yaya money</option>

</select>

</div>

<br>
<div>
<label for="agree">agree</label>
<input type="checkbox" id="agree" name="agree">
</div>
<br>

<div>
<input type="reset">
</div>


<br>

<div>
<input type="submit">
</div>

    </form>
</body>
</html>


