# UoNHockey.club instructions

Editing the website can seem like a minefield at first but really its pretty simple if you follow these steps.

## New post
To add a new post, make a copy of one of the posts in the `_posts` folder. 
* Change the file name to be the date in `YY-MM-DD` format followed by a few word description (don't use spaces here)
* Change the header information (title, author [`gil` or `UoNHockey`], category, tags, image [see below for further details])
* Edit the body of the post underneath the `---` line. 
  **  It's formatted with *github flavoured markdown*, more info on how this works is availible here: https://guides.github.com/features/mastering-markdown/ 
  ** An online editor can be used to make this process a bit quicker and more interactive so you'll see roughly what you'll get https://markdown-editor.github.io/
  
## Images
Images need to be handled carefully otherwise they won't show up and things will look terrible. 
All images need to be uploaded into the folder `assets/images/`. Name them something easy to refer to. For example if you want to upload a picture of a 1s player, call it `200928-1sBrownlee.png` (note `200928` is just a date `YYMMDD`)
### Post headers
The image referred to in the post header will appear on the home page in the post feed, and also at the top of the post page. It should be landscape, decent quality.
To use the example above, it should be referenced as `image: assets/images/200928-1sBrownlee.png`.

### In post images
You might want to add another image inside the content of the post. 
To do this, upload the image as before to the folder `assets/images/`. Then in the post body, you can insert an image one way by putting `![A description of what the image shows](\assets\images\200928-1sBrownlee.png) `. Here the link to the folder containing the image (NOTE THE `/` at the start) is given.
