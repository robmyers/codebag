# Code Bag

I think most developers end up with an assortment of random code -- each piece too small to be a "project" but large enough to want to keep around as an example or something useful.

I'm collecting some of the random scripts or bits of code that I've shared into one repository.

## Organization

I'm using the word pretty loosely.  Things are piled into directories roughly organized the kind of code it is -- either purpose or language.

This README may not inventory all of it.

## Python

[Python][] is a handy programming language.

   - python/rounded-corners -- generate rounded corners for use with CSS to roundify boxes; obsolete with modern browsers using PIL.
   - python/mergeframe -- Merge a framing image with another image using PIL.
   - python/uuids.pyx -- A poor binding of libuuid to Python using Pyrex; written to play with Pyrex.
   - python/imagepdf.py -- Assemble a bunch of images into a PDF using ReportLab (to make the PDF) and Singleshot (to read IPTC tags for captions).
   - python/gpx2polyline.py -- An old script to take a GPX track and
     turn it into some JavaScript to render a plot on Google Maps.
   - python/schedule.py -- An old script that plots Caltrain schedules
     as a graphic.

## LambdaMOO

[LambdaMOO][] is a MUD server.  It is a programmable chat server.
That simplifies things a bit since one could write non-chat networked
applications on top of LambdaMOO.

This has its own [README](https://github.com/xythian/codebag/tree/master/moo).

[wp-lambdamoo]: http://github.com/xythian/wp-lambdamoo
[Python]: http://www.python.org/
[PIL]: http://www.pythonware.com/products/pil/
[pygame]: http://www.pygame.org/
[SDL]: http://www.libsdl.org/
[pyrex]: http://www.cosc.canterbury.ac.nz/~greg/python/Pyrex/
[reportlab]: http://www.reportlab.org/
[LambdaMOO]: http://www.lambda.moo.mud.org/
