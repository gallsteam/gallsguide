# Getting Started

!> Please contact **moore-john@galls.com** for any problems or suggestions.

The Galls front-end is built on the Bootstrap Framework and you can take advantage of most functionality seen in their [documentation](http://getbootstrap.com/css/). Please read and familiarize yourself with the CSS and components.

This documentation is hosted on [Github](https://github.com/gallsteam/gallsguide_written) with Markdown, you may use this [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code) to learn and update this guide.
## Downloads
Coming soon.


# Fonts

**Title Font: **
[Rajdhani](https://fonts.google.com/specimen/Rajdhani?selection.family=Rajdhani:500,600,700)

We use font-weights 500, 600, and 700. Please use 700 for all primary titles, 600 for sub-titles, and 500 for sentences.

    font-family: 'Rajdhani', sans-serif;
    font-weight: 700;

**Body Font: Helvetica**

Use Helvetica for all paragraphs and areas that require easy readability.


    font-family: 'Helvetica', Arial, sans-serif;

# Colors

* <font color="#007ac2">Blue #007ac2</font>
* <font color="#de5101">Galls Orange #de5101</font>

# Images

!> All images must be saved as .JPG and ran through [ImageOptim](https://imageoptim.com/) before going live.

# Responsive Helpers
Coming soon.

# Homepage

Hero image with text built into the graphic: You may add in-line styling to the div if you need to overwrite the default styling. Padding must always be specified in this type of component.
```html
<main class="body">
<div class="container hero-banner" style="background-image: none;height: auto;padding: 0px;">
	<a href="/linkhere" onclick="ga('send', 'event', 'newhero', 'click', 'Event name');" title="Title">
		<img class="img-responsive hidden-xs-sm" alt="Alt tag here" src="/photos/gar/images/hero/imagename.jpg" />
		<img class="img-responsive visible-xs-sm" alt="Alt tag here" src="/photos/gar/images/hero/imagename.jpg" />
	</a>
</div>
```

# Category


# Brand