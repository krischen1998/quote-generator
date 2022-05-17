# quote-generator

### You can clone this repo and run this program on your local machine (python virtual environment).

### Or you have the option to send GET requests to the URL: https://quote-generator-app-kc.herokuapp.com/

**Example Usage:**

<br>

**You can add your keyword as a parameter:**

GET https://quote-generator-app-kc.herokuapp.com/happy

**The response you get is:**

{"Quote":"Happiness, true happiness, is an inner quality. It is a state of mind. If your mind is at peace, you are happy. If your mind is at peace, but you have nothing else, you can be happy. If you have everything the world can give - pleasure, possessions, power - but lack peace of mind, you can never be happy."}


<br>


**When you enter a keyword that can't be found:**

GET https://quote-generator-app-kc.herokuapp.com/fsadkljfokas

**The response you get is:**
{"Error":"No quotes found, Please try again or change another keyword"}
