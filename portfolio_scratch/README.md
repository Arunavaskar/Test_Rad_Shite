# Steps to follow

1. Installing node.js
    * Create a file called package.json for handling all the dependencies.
    * run `npn init` in the project folder terminal and hit enter.
    * Now enter a package name to the package 
    * Skip on changin the version
    * Add a good description
    * Skip adding git repo and test commands
    * Enter keywords like "Bootstrap portfolio_scratch sass learn-bootstrap learn-sass"
    * Enter author name like your's
    * Skip with the liscenece
    * Double check everything
    * Hit enter to complete

## SASS Setup

**Now we should have a file named package.json in the project folder. Now we are going to add/install the package to be used in this project**

2. Package list
    1. Dart-sass
    It is a pre-processor for converting sass to css
    2. Bootstrap 5
    3. FontAwesome
    FontAwesome is going to help us with the icons and fonts
    4. AutoPrefixer
    AutoPrefixer helps with the monotony of writing prefixes for css

3. Got to [npmjs.com](https://npmjs.com) and search for dart-sass and select the one that sayss "A pure javascript implementation of Sass."
    * Now scroll down the page to the "Usage" section and copy the `npm install --save-dev sass` and this one will add sass to your project. It provides executable and library as well.

4. Now we are going to install bootstrap. 
    * Use `npm install bootstrap --save` in the terminal.
    * `--save` will allow bootstrap to be installed as a dependency for the project. 

5. Now we are going to install FontAwesome by going to [fontsawesome.com](https://fontsawesome.com)
    * Click on the start for free button
    * Now scroll down the page to find out the npm section and then click on it
    * Now copy the first free version font npm package using this `npm install --save @fortawesome/fontawesome-free`

6. Now we are going to install Autoprefixer.
    * Go to [npmjs.com](https://npmjs.com) and search for postcss-cli install command.
    * Or just use this `npm install postcss-cli autoprefixer --save`.

Now we are going to start working our project and we are going to install other packages as the needs arises. 

7. Now we will create a `npm` script which is going to compile our Sass to css. In the 'package.json' file you will see scripts object with some predefined scripts. We will now add our own scripts here.

    *Refer to this article for better explaination on to how this scripting synatx works [freecodecamp](https://www.freecodecamp.org/news/introduction-to-npm-scripts-1dbb2ae01633/).*

    `"compile:sass":"sass --watch scss:assets/css"`
    
    * `compile:sass` is the name/keyword of the script to be run
    * `"sass scss:assets/css"` means that any `sass` type file from "scss" named folder will be compiled and the output will be added to "assets/css" folder. 
    * `--watch` is a flag that makes the script running continuously and watches for any changes being made to the `Sass` file and compiles the script on the fly. 
    
    **You will find "style.css.map" file inside the "assets/css" folder after the `Sass` compilling is done.**
    
    **Source maps are files that tell browsers or other tools that consume `CSS` how that `CSS` corresponds to that `Sass` files from which it was generated.**

    **They make it possible to see and even edit your `Sass` files in browser.**
    
## Customizing Bootstrap

8. 

