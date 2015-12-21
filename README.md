![](http://image.noelshack.com/fichiers/2015/52/1450692669-polymerawesome.png)
## Polymer Awesome Kit
> The Polymer Starter Kit with few improvements....

### Included out of the box:
* [Polymer Starter Kit 1.2.1](https://github.com/polymerelements/polymer-starter-kit/releases)
* [Jade template engine](http://jade-lang.com/)
* [Sass](http://sass-lang.com/)
* [CoffeeScript](http://coffeescript.org/)

## Getting Started

There is nothing different than the [Polymer Starter Kit](https://github.com/PolymerElements/polymer-starter-kit) on how to use it but the structure of the elements is now separated in 3 parts (**CoffeScript (javascript) file**, **Jade (HTML) file**, **SCSS (CSS) file**). Lint has also been deactivated. 

![](http://image.noelshack.com/fichiers/2015/52/1450693863-capture-d-ecran-2015-12-21-a-11-30-35.png)

* Install the dependencies with `bower install` & `npm install`. 
* Use `gulp serve` to start a local test environment. Any changes on the *CoffeeScript, the Jade and the SASS files* are directly compiled and served in the browser. 
* Use `gulp serve:dist` to start a local dist environment or `gulp`to just compile everything and push the files on your FTP. 

The `gulp` and `gulp serve:dist` commands are directly compiling, minifying, vulcanizing, embedding the code and cleaning the repertories.

![](http://image.noelshack.com/fichiers/2015/52/1450694633-jadesass.png)

-----

#### Using Sublime Text and having Jade indentation problems ?
Follow this url : http://stackoverflow.com/questions/18343651/jade-indentation-errors