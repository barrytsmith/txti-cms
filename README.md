# Using txti.es to make the world's smallest CMS

Turn any html page into a Markdown-driven CMS using [txti.es](http://txti.es) and just 25 lines of JavaScript. 

[View a demo](http://barrytsmith.com/lab/txti-cms/).

## Step 1

Create an HTML file. Each element that you would like to populate with HTML from a [txti](http://txti.es) page should get and attribute of `data-src="http://txti.es/your-unique-url-here/html"`.

If you haven't created the txti pages yet, do so in this step. Be sure to email all information to yourself in the process so you can make changes later.

## Step 2

Past in the `<script>` tag in the index.html file above right before the closing `</body>` tag of your HTML file. You're done! You should get nice, clean HTML delivered from txti. (You can also include or paste the code from the txti-cms.min.js file for a compressed version)

Because this solution requires JavaScript, it's recommended you put some helpful text with a link to the txti page inside of the element in case the user has JavaScript disabled. Txti itself uses no JavaScript and is lighting fast, so the content will be available.

## Update your site by updating your txti files 

Txti uses GitHub flavored [Markdown syntax](http://txti.es/how).
