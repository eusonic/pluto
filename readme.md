#Pluto
A heavily personalized, shamelessly derivative, and delightfully minimal html5 base theme for Drupal.

##Philosophy
Pluto is designed to work with my particular coding style, and for the particular kinds of sites that I build (mostly large institutional websites). In general, I would rather spend time adding stuff to a theme than taking it away. For this reason, there are basically no design or layout styles provided. Another guiding principal is that as much as possible should be provided by blocks, rather than baked into the theme. For this reason, a lot of common theme features are left out (such as navigation, site title, or site header image). You'll have to create blocks for these things.

##Some Features
- [Modernizr](http://modernizr.com/) built in.
- Wherever possible, Pluto uses the [HTML5 Boilerplate](http://html5boilerplate.com/).
- Compass (Sass) for css. You will need to install Compass and compile
- 3 column layout (The regions are there, but you have to add css).

##To Do
- Modernizr is not being loaded because the filename is wrong in the .info file.
- Document stylesheets within readme
- Screenshot
- logo
- breadcrumbs
- think more about the role of global/_page-components.less. Rewrite the documentation, or possible remove the file.

##Shamelessly derivative
Pluto borrows heavily from the following projects:
- [HTML5 Boilerplate](http://html5boilerplate.com/)
- [Boron theme](http://drupal.org/project/boron)
