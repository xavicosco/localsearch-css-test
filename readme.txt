Local Search - CSS Layout Task
------------------------------

Steps to generate css from sass/scss:
-------------------------------------
1. open terminal
2. cd {path directory}
3. gulp and npm should be installed
4. run gulp
5. .css file is generated and minified inside folder build
6. open index.html in a browser

I created a basic gulp file to automate some basic processes such as:
- sass to generate css
- rename file (to add .min.js)
- minify file, which means that the file is less heavy on a server, enhance of performance.

Thoughts:
---------
- As this task is fairly simple, I used pixel units to display on a static layout.
- On a better approach should be used rem or % units to make it responsive and mobile-friendly.
- All code is hard coded instead of loading from a json or xml object.
- Majority use of element classes instead of id. ID should be unique on each page. But because in terms of code scalability and dynamic load I used classes.
- Pixel perfect design has been double checked on all evergreen browsers. Use of Photoshop as well to check it.
- Use of sprite of icons which enhance the performance of the server, only one call. Whereas single images (.png) means multiple calls. Best solution is to use font typography (allow resizing without loss of quality and can change colors).
- To generate scalable vector icons (SVG), this website is pretty useful: https://icomoon.io/app/#/select
 

