# Slidex

A simple custom slideshow template built on HTML, CSS and JS

## Usage

This software/template is recommended for making custom Slideshows.  Bored with Powerpoint Presentations?  Bored with Google Drive Presentations?  Got too much time to waste?  Use Slidex!  Slidex allows you to create your very own custom Powerpoint-style presentation using only HTML, CSS and Javascript!

Being built on pure *HTML, CSS and JS* means that Slidex is customizable *to the core*.  While Powerpoint slides and Google Presentations are also highly customizable in the sense that you can change the background theme, font size, font color and so on, its customizability in certain areas are very limited.  For example, you cannot even display a very simple game on a Powerpoint or a Google Slide.  Slidex, however, can easily overcome this - as long as you know how to code it, nothing is impossible in Slidex.  You can style your own links and buttons, decide exactly what shows up on each slide and how they interact with the user ... and so on.  The possibilities are just endless.

In case you are not familiar with CSS or Javascript and are struggling to style a single button - no problem!  Slidex comes with a number of crucial pre-styled elements, including 2 types of buttons and custom links that look much nicer than the default.

## Instructions

It does not require much skill to use the core features of Slidex.  For example, in the HTML file, find the inline script that initializes the Slidex app.  You will probably see something like this:

```js
slidex.init({
  // fontFamily: "monospace",
  color: "white",
  backgroundColor: "black"
});
```

In ```Slidex```, there are only 3 properties to modify: ```fontFamily```, ```color``` and ```backgroundColor```.  You can choose to modify all 3 properties, but you can also choose to modify any (other) combination of properties.  You can even choose to not modify anything at all (```slidex.init()```)!  If you do not choose to modify any settings, Slidex defaults to a white background and black text.

In case you want special styling for a particular slide or section, just do inline styles (e.g. ```<p style="color: red;">A custom red paragraph!</p>```) or just link your custom stylesheet to the HTML file!

## License

(c) Donald Leung.  All rights reserved.

This project is MIT Licensed.  See [LICENSE](https://github.com/DonaldKellett/Slidex/blob/master/LICENSE) for details.
