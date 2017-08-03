# portfolio-frame-rate-optimization
The following website has been optimized to deliver to give a 90+ pagespeed score.(varies a bit depending on network)
The performance issues have been delt with to give a lag free 60fps experience

## Optimizations done in app.js
1. querySelector have been replaced by getElementById,getElementsByClassName.
2. Some of the calculations have been taken out of the loop which needed to be performed only once like width,dx(name of the variables has changed due to minifiaction).
3. document.body.scrollTop has been taken out of the loop.
4. No. of pizzas has been reduced to 30.

## How to run
There are two folders:
* Minified version:It can be used to test the pageinsights score and 60 fps test.
* Uminified version:It does not deliver 90+ pageinsight score but is usefull if someone wants to read code.
