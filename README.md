<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
    <title>USER EXPERIECE RESERACH SURVEY</title>
    <style>
body{
   background-image: url("online picture.jpg");
   background-size: 100%;
}
@media screen and (min-width: 600px) {
  div.example {
    font-size: 80px;
  }
}

@media screen and (max-width: 600px) {
  div.example {
    font-size: 30px;
  }
div{
background-color: #a8e063;
outline-style: dotted;
}
    </style>
</head>
<body>
<center>
<div class="maggie">
    <form action="/action_page.php" method="POST">
            <h1>UI/UX Research Survey</h1>
            <hr  width=50% />
            <h3>How did you learn about our app?</h3><br />
            <select id="APP" name="APP">
                <option value="select option">Select option</option>
                <option value="Search engine">Search engine</option>
                <option value="Facebook">Facebook</option>
                <option value="Twitter">Twitter</option>
                <option value="Instagram">Instagram</option>
                <option value="play store">Play store</option>
                <option value="Another website">Another website</option>
                <option value="Other text">Other text</option>
              </select>
<H3>How was your experience using our app for the first time?</H3><br />
<input type="radio" name="first" value="Ecellent" />
     <label for="Excellent"> Excellent</label>    
<br>
<input type="radio" name="first" value="Very good" />
    <label for="Very good"> Very good</label>     
<br>
<input type="radio" name="first" value="Neutral" />
     <label for="Neutral"> Neutral</label>    
<br>
<input type="radio" name="first" value="Bad" />
      <label for="Bad">Bad</label>   
<br>
<input type="radio" name="first" value="Poor" />
    <label for="Poor"> Poor</label>     
<br>
<H3>How likely are you to recommend our app to a friend or colleague?</H3><br />

<input type="radio" name="recommend" value="Very likely" />
         <label for="Very likely"> Very likely</label> 
<br>
<input type="radio" name="recommend" value="Likely" /> 
       <label for="Likely"> Likely</label>   
<br>
<input type="radio" name="recommend"  value="Not sure" />
     <label for="Not sure"> Not sure</label>    
<br>
<input type="radio" name="recommend"  value="Unlikely" />  
        <label for="Unlikely"> Unlikely</label>
<br/>
 <input type="radio" name="recommend" value="Not likely at all" />
        <label for="Not likely at all"> Not likely at all</label>
<br/>
<H3>How easy to use is our app?</H3><br />
<input type="radio" name="app" value="Very easy" />
<label for="Very easy"> Very easy</label>
<br>
<input type="radio" name="app" value="Easy" />
<label for="Very easy"> Very Easy</label>
<br>
<input type="radio" name="app" value="Uneasy" />
<label for="Uneasy"> Uneasy</label>
<br>
 <input type="radio" name="app" value="Not easy at all" />
 <label for="Not easy at all"> Not easy at all</label>
<br>
<H3>How satisfied are you with the following?</H3><br />
<table border="1">
    <tr>
        <th></th>
        <th>Very Satisfied</th>
        <th>Satisfied</th>
        <th>Neutral</th>
        <th>Dissatisfied</th>
        <th>Very dissatisfied</th>
    </tr>
    <tr>
        <td>Quality of app</td>
        <td><input type="radio" name="app" /></td>
        <td><input type="radio" name="app" /></td>
        <td><input type="radio" name="app" /></td>
        <td><input type="radio" name="app" /></td>
        <td><input type="radio" name="app" /></td>
    </tr>
    <tr>
        <td>User-friendliness</td>
        <td><input type="radio" name="friendliness" /></td>
        <td><input type="radio" name="friendliness" /></td>
        <td><input type="radio" name="friendliness" /></td>
        <td><input type="radio" name="friendliness" /></td>
        <td><input type="radio" name="friendliness" /></td>
    </tr>
    <tr>
        <td>Ease of use</td>
        <td><input type="radio" name="use" /></td>
        <td><input type="radio" name="use" /></td>
        <td><input type="radio" name="use" /></td>
        <td><input type="radio" name="use" /></td>
        <td><input type="radio" name="use" /></td>
    </tr>
    <tr>
        <td>Payment process</td>
        <td><input type="radio" name="process" /></td>
        <td><input type="radio" name="process" /></td>
        <td><input type="radio" name="process" /></td>
        <td><input type="radio" name="process" /></td>
        <td><input type="radio" name="process" /></td>
    </tr>
    <tr>
        <td>Customer service</td>
        <td><input type="radio" name="service" /></td>
        <td><input type="radio" name="service" /></td>
        <td><input type="radio" name="service" /></td>
        <td><input type="radio" name="service" /></td>
        <td><input type="radio" name="service" /></td>
    </tr>
</table>
<H3>What feature do you like most?</H3><br />
<textarea name="feature" rows="20" cols="100"></textarea><br />
<br />
<H3>What would you like us to improve</H3><br />
<textarea name="improve" rows="20" cols="100"></textarea>
<H3>Rate our app</H3><br />
<p style="font-size:48px">
    &#128512;
        &#128516;
        &#128525;
        &#128151;
       </tr> 
    </p>
    <input type="submit" value="Submit">
      </center>
    </form>
</div>
</body>
</html>
