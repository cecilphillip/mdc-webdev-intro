## Instructions
In this exercise, we're going to add some JavaScript!

1. Open index.html in your browser.
2. Try clicking on the Toggle button
2. Open index.html in your editor
3. Right above the ``` </body> ``` tag, add the following lines.
```
    <!-- jQuery -->
    <script src="js/jquery.js"></script>

    <!-- Bootstrap JavaScript -->
    <script src="js/bootstrap.min.js"></script>

    <!-- Your Script -->
    <script src="js/site.js"></script>
```
4. Save the file again and refresh the browser.
5. Try clicking on the Toggle button again
6. Try clicking the `About` item in the side menu
7. Now open up site.js
8. Just above the last line of JavaScript in that file, paste the following code.
```
$(".sidebar-nav a").click(function (e) {
    alert("Navigation Engaged");
});
```
9. Save the file again and refresh the browser.
5. Click the Toggle button and try clicking the `About` item again.