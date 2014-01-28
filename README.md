# Stubble

## A front-end base for your websites

Stubble is a custom front-end base code intended for small projects, that I put together for my personnal use. Because it it relatively flexible, I thought others might like to use it as well, so I decided to share it publicly. Although I tried my best to stick to best practices and standards, please bear in mind that this project is the result of an opiniated work.

## Technologies and resources

This project uses the following popular technologies and add-ons:

* HTML5 and CSS3
* [SASS](http://sass-lang.com/) CSS extension
* [jQuery](http://jquery.com/) JavaScript library
* [Modernizr](http://modernizr.com/) JavaScript library
* [Smooth-Scroll.js](http://cferdinandi.github.io/smooth-scroll/) JavaScript add-on
* [Normalize.css](http://necolas.github.io/normalize.css/) resets

I also added some optional resources which I like to use, namely:

* [HTML5 Boilerplate](http://html5boilerplate.com/) styles (modified)
* [Toast.css](https://daneden.me/toast/) grid system (modified)
* [Animate.css](http://daneden.github.io/animate.css/) animations (unmodified)

It goes without saying that this is just a starting front-end base, which should accomodate everyone's requirements. Feel free to remove some bits, tweak others and write your website's code on top of it. You can easily enable/disable resources in `assets/css/sass/main.scss` and `assets/js/main.js` at anytime.

## SASS configuration

In its default state Stubble uses SASS for the styles. The stylesheets you will work in are all localed in `assets/css/sass/`. The files beginning with an underscore are includes and can be enabled/disabled in `main.scss`.

    assets/
    |   css/
        |   main.min.css
        |   sass/
            |   _animate.scss
            |   _fonts.scss
            |   _html5boilerplate.scss
            |   _mixins.scss
            |   _normalize.scss
            |   _responsive.scss
            |   _shame.scss
            |   _site.scss
            |   _toast.scss
            |   main.scss
        
In my local development environment I use [Compass](http://compass-style.org/) or sometimes [LiveReload](http://livereload.com/) to compile SASS into standard CSS. I configure the software so it compresses the resulting code and stores it in `main.min.css`. This is the only stylesheet file that is called in the HTML.

## Toast grid system

Toast is a very simple and easy-to-use grid system. In order to use it just create a div with the class `.grid` and add as many units as you need inside it as shown in the demo below. For more information about Toast please visit the [author's website](http://daneden.me/toast/).

    <div class="grid">

        <div class="unit one-of-three">.unit.one-of-three</div>
        <div class="unit two-of-three">.unit.two-of-three</div>

        <div class="unit one-of-two">.unit.one-of-two</div>
        <div class="unit one-of-two">.unit.one-of-two</div>

        <div class="unit three-of-five">.unit.three-of-five</div>
        <div class="unit two-of-five">.unit.two-of-five</div>

        <div class="unit span-grid">.unit.span-grid</div>

    </div>

## Why is it called 'Stubble'?

Every great beard starts with stubble. Every great website starts with a solid base. Shape it as it grows, make it remarquable, take pride in your work.

## Have questions? Want to contribute?

Feel free to get in touch via social media or email if you have any questions or comment. Although it is open-source, this is more of a personnal project, which means that I'm not particularly looking for anyone to get involved here. Having said that, I'm always learning and improving my ways, so this project is likely to evolve fairly regularly which might include your contributions.
