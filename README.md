[![The Stanford Daily logo](https://github.com/TheStanfordDaily/stanforddaily-graphic-assets/raw/master/DailyLogo/DailyLogo.png)](https://www.stanforddaily.com/)

# The Stanford Daily WordPress Theme
This is the WordPress theme for the Stanford Daily website. See it live at https://www.stanforddaily.com/. Contributions welcome!

## Local setup
See https://github.com/TheStanfordDaily/stanforddaily-website/.

## Theme Development
The theme is using [Sass](https://sass-lang.com/) for styling. When developing the theme, you should be editing individual `.scss` files in the `sass/` folder. Do NOT manually edit the `style.css` file.

We are using [Grunt](https://gruntjs.com/) to compiling files.

To set up, type the following command in the theme folder (`wp-content/themes/thestanforddaily/`)
```
npm install -g grunt-cli
npm install -g sass
npm install
```

Then just type the following command every time you start working on the theme:
```
grunt
```

If you see:
```
Running "watch" task
Waiting...
```

It means that grunt is up and running. Grunt will watch your `scss` files changes and automatically update the `style.css` and `style.min.css` for you.
