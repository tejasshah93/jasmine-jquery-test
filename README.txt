- This uses Jasmine Library(https://github.com/pivotal/jasmine) to unit test the html form "demo.html" found in the root directory. This tests accesses the DOM by using a jquery click against an html fixture reproduction using jasmine-jquery (https://github.com/velesin/jasmine-jquery). It does test validation against the DOM as well also using this library.

- To watch tests failing, change "$(".showButton").click()" to "$(".hideButton").click()" in "index.js".
Conversely, change "$(".hideButton").click()" to "$(".showButton").click()" and watch a different group of tests fail.  

- Running the tests
Just run index.html in your browser and watch the results of tests
demo.html is the dynamic html being tested