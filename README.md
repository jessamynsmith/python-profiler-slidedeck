# Python Profiling Introduction
        
This slide deck is based on the Ladies Learning Code slide deck, which includes features such as incremental display of content, interactive CSS demos built into the slides, markdown integration and presenter notes. Check out the original slide deck at http://ladieslearningcode.github.io/llc-slidedeck-template/slides.html for details.

Created with <a href="https://github.com/LeaVerou/csss/sample-slideshow.html">Lea Verou's CSS-based SlideShow System</a> and <a href="http://lab.hakim.se/reveal-js/">reveal.js</a>. Syntax highlighting courtesy of http://highlightjs.org. Best viewed in Chrome or Firefox.

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.


### Development

Compile css:

    sass --watch framework/sass/:framework/css/

View slides:

    Open framework/index.html in the browser
    
To see presenter notes:

    With framework/index.html open in the browser, press Ctrl+P or Shift+P


### Heroku

    heroku buildpacks:add https://github.com/hone/heroku-buildpack-static.git
