<DOCTYPE html>
  <html lang="en">
      <meta charset="UTF-8">
      <title>Registration Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

<body>
  <h1 id="title"> Survey Form </h1>
  <p id="description"> Thank you for taking the time to fill out this survey! </p>
 <fieldset>
   
 <form id="survey-form"> 
   <label id="name-label" for="name"><fieldset> Name:
   <input type="text" id="name" placeholder="John Doe" required </input> </label> </br>
<label id="email-label" for="email"> Email:
  <input type="email" id="email" placeholder="johndoe123@gmail.com" required </input> </label> </br>
 <label id="number-label" for="number"> Age:
   <input type="number" id="number" placeholder="18-120" min="18" max="120" required </input> </label> </br>
<label> What is you career goal?
  <select id="dropdown"> <option value="">Select One</option>
   <option value="1">Computer programmer</option>
   <option value="2"> Web developer</option>
   <option value="3"> Software developer</option>
   <option value="4"> Full stack developer</option>
   <option vale="5"> Other</option> </select> </fieldset></label></br>
  
<label><fieldset>How passionate are you about coding?</label> <br> 
    <label><input type="radio" name="learning-level" class="inline" value="a" /> Very passionate </label> </br>
    <label> <input type="radio" name="learning-level" class="inline" value="b" /> Somewhat passionate </label> </br>
    <label> <input type="radio" name="learning-level" class="inline" value="c" /> Not passionate </fieldset></label> </br>

    <label><fieldset> What do you love most about coding? (check all that apply)</label> </br>
<label><input type="checkbox" value="11" />Problem Solving</label> </br>
<label><input type="checkbox" value="12" />Always learning</label> </br>
<label><input type="checkbox" value="13" />Working on cool prjects</label> </br>
<label><input type="checkbox" value="14" />Being part of a passionate community</fieldset></label></br>

<label><fieldset>Additional comments:<textarea name="comments" rows="3" cols="30" placeholder="Comment here..."></textarea></fieldset> </label>

<label><fieldset><input id="submit" type="submit" value="Submit"></fieldset></label>
    
    </fieldset>

 </form>
</html>