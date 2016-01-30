* Read [Quick tour of Polymer](https://www.polymer-project.org/1.0/docs/start/quick-tour.html)
* Get `bower` [A package manager for the web](http://bower.io/#install-bower)

          npm install -g bower

* `bower init` (See [bower.json specification](https://github.com/bower/spec/blob/master/json.md))
* [Get the Polymer library](https://www.polymer-project.org/1.0/docs/start/getting-the-code.html)

            bower install --save Polymer/polymer#^1.2.0

* If you try to open the file `index.html` an error occurs (see the console) 

             Imported resource from origin 'file://' has been blocked from loading 
             by Cross-Origin Resource Sharing policy: Invalid response. 
             Origin 'null' is therefore not allowed access.

* Instead do `npm install -g http-server` (a static server)
* Run `http-server`
* Visit the page [http://127.0.0.1:8080/](http://127.0.0.1:8080/)
