angular-java-server-midi
========================

Compiling
---------
	mvn install


Running in Jetty
----------------
	mvn jetty:run

Then open <http://localhost:8080/> and play the piano. You can now edit your HTML and
Javascript and press reload in the browser to test your updates.


Manual Jasmine Spec Runner
--------------------------
After a build you will find a manual spec runner: /target/jasmine/ManualSpecRunner.html.
This is very useful to use while you are developing Angular controllers and Jasmine
specifications.

