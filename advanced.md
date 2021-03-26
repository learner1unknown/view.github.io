<!DOCTYPE html>
<html lang="en">
    <link rel="stylesheet" href="advanced_search_style.css">
    <nav>
        <ul>
       <li><a href="/index.md">Google Search</a></li>
       <li><a href="/advanced.md">Advanced Search</a></li>
       <li><a href="/image.md">Image Search</a></li>
       <li><a href="/lucky.md">I'm Feeling Lucky</a></li>
    </ul>
    </nav>

    <head>
        <title>Advanced Search</title>
    </head>

    <body>
        <img src="googlelogo.png" alt="Google">
        <form action="https://www.google.com.au/search">
                <h4>Find pages with...</h4>
                <div>
                  <label for="as_q">all these words:</label>
                  <input type="text" name="as_q" id="as_q" />
                </div>
                <div>
                  <label for="as_epq">this exact word or phrase:</label>
                  <input type="text" name="as_epq" id="as_epq" />
                </div>
                <div>
                  <label for="as_oq">any of these words:</label>
                  <input type="text" name="as_oq" id="as_oq" />
                </div>
                <div>
                  <label for="as_eq">none of these words:</label>
                  <input type="text" name="as_eq" id="as_eq" />
                </div>
                <input type="submit" value="Advanced Search">
        </form>
    </body>
</html>
