# Survey-form
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="uft-8">
  <link rel="stylesheet" href="stylesheet.css">
  <meta name="viewpoint" content="width=device-width,initial-scale=1.0"/>
<h1 id="title"><bold>Do you lead a healthy livestyle?</bold></h1>
<p id="description"><b>In this survey you will be required to answer a few questions that will help us determine how healthy are you day to day choices</b>b></p>

</head>
<body>
  <fieldset>
  <form id="survey-form">
    <label class="inline" id="name-label">Introduce your name:<input required type="text" name="name" id="name" type="text" name="name" placeholder="Enter your name"></label>
<label class="inline" id="email-label">Introduce your email for the results:<input required id="email" type="email" name="email" placeholder="Enter your email"></label>
<label class="inline" id="number-label">Introduce your age:<input type="number" id="number" name="number" min="18" max="100" placeholder="Enter your age"></label>

 <p>What type of food do you eat the most:</p>
<select id="dropdown" class="inline">
  <option>Fast food</option>
  <option>Home-cooked meals</option>
  <option>Restaurant food</option>
  <option>Frozen food</option>
  <option>Pastry</option>
  <option>Desserts</option>
  </select>

<p>How much sport are you doing daily</p>
   
 <div class="sport">
    <label for="none">
        <input type="radio" id="none" name="time" value="none">Close to none
    </label>
</div>

<div class="sport">
    <label for="10">
        <input type="radio" id="10" name="time" value="10">At least 10 minutes
    </label>
</div>

<div class="sport">
    <label for="10-30">
        <input type="radio" id="10-30" name="time" class="sport" value="10-30">Between 10 and 30 minutes
    </label>
</div>

<div class="sport">
    <label for="30">
        <input type="radio" id="30" name="time" class="sport" value="30">At least 30 minutes
    </label>
</div>

<div class="sport">
    <label for="30-1">
        <input class="sport" type="radio" id="30-1" name="time" value="30-1">Between 30 minutes and an hour
    </label>
</div>

<div class="sport">
    <label for="1h">
        <input type="radio" id="1h" name="time" class="sport" value="1h">Over an hour
    </label>
</div>

 <legend <div class="sport">
    <label for="none">
        <input type="radio" id="none" name="time" value="none">Close to none
    </label>
</div>

<div class="sport">
    <label for="10">
        <input type="radio" id="10" name="time" value="10">At least 10 minutes
    </label>
</div>

<div class="sport">
    <label for="10-30">
        <input type="radio" id="10-30" name="time" class="sport" value="10-30">Between 10 and 30 minutes
    </label>
</div>

<div class="sport">
    <label for="30">
        <input type="radio" id="30" name="time" class="sport" value="30">At least 30 minutes
    </label>
</div>

<div class="sport">
    <label for="30-1">
        <input class="sport" type="radio" id="30-1" name="time" value="30-1">Between 30 minutes and an hour
    </label>
</div>

<div class="sport">
    <label for="1h">
        <input type="radio" id="1h" name="time" class="sport" value="1h">Over an hour
    </label>
</div>

<p>How are you relaxing your body and mind</p>

 <label for "relaxing"><input type="checkbox" id="relaxing" value="relaxing">You spend at least 20 minuts a day doing something you find relaxing</label>
  <label for "reading"><input type="checkbox" id="reading" value="reading">You read at least two hours per week</label>
   <label for "outside"><input type="checkbox" id="outside" value="outside">You spend at least an hours per day outside</label>
   <label for "screentime"><input type="checkbox" name="screentime" value="screentime">You limit your screentime as much as possibl</label>
   
   <p>Here you can add additional details about your diet, the type of sport you are practicing or your recreational activities for a more accurate result</p>
<textarea></textarea>
   <hr>
   
   <button type="submit" id="submit">Submit</button>
  </form>
  </fieldset>

</body>
 <footer><b>This quiz does not replace the expertize of a doctor. Please consult a specialist if you have any doubts that you are meeting all the requirments to lead a healthy livestyle.</b>b></footer>

</html>
