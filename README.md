# jQuery Practice with fadeIn() and fadeOut()

#### Look at index.html
- What class is on every `<div>` that has a word inside?

#### In script.js
- Select all of the word boxes using their class and save them in a variable called words like this:
  - ``` var words = $(".words"); ```
- The first thing we want to do is make all of the words fade out.
  - ``` words.fadeOut(); ```
- Let's use `fadeIn()` to show the words "we love to code"
  - Select `<div>` with "we" inside and save it in a variable 
    - ``` var we = $("#we");```
  - Use fadeIn() to fade this word back in.
    - ``` we.fadeIn(); ```
  - Continue this same process for the words "love", "to", and "code"
- Make the words fade in more slowly. *HINT* look here: [https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_fadein](https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_fadein)


#### In style.css
- Add a background color to your page.
- Make your background color a [linear-gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient)


BONUS
- Change your message to say something different when it fades in.
- Add a [google font](https://fonts.google.com/) to your page. Hint: you may want to google how to add
  - Click on the red plus sign of the font you want to use
  - Click on the black bar at the bottom of the page that says 1 Family Selected
  - Copy the `<link>` and put it inside the `<head>` tag in your HTML
  - Follow the font-family instructions for your CSS




## WEEK 5: HOMEWORK!
* Go to www.repl.it
* Login
    - username: yourfirstname_yourlastname
    - password: hwstudio5122
* Click on our Web Development classroom
* Find the week 5 assignment