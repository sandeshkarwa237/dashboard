<h1>7:1 architecture pattern</h1>

This is architecture model Sass "7:1 architecture pattern", consisting of 7 folders and 1 file. The entire project style is divided into files within 7 folders, and a single root file imports all files into a single style sheet.

<pre>
scss/
|
|– abstracts/
|   |– _variables.scss    # Variables Sass
|   |– _mixins.scss       # Mixins Sass
|
|- components/
|   |- _buttons.scss      # Buttons
|   |- _forms.scss        # Inputs style
|   …                     # Etc.
|
|- layout/
|   |- _navigation.scss   # Navigation
|   |- _header.scss       # Header
|   …                     # Etc.
|
|- themes/
|   |- _night.scss        # Night theme
|   …                     # Etc.
|– style.scss              # Sass main file
</pre>


