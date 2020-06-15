# Bias and Equity in Tech Reading List

## Another reading list?

After kicking off my recommendations for a bias and equity in tech starter pack, many of y'all wanted to see more! And also wanted to add your own suggestions! Here's the answer. 

If you'd like to add a suggestion, use this example to [open a pull request](https://github.com/lorenanicole/tech-bias-equity-reading/pull/1). In short you'll need to add two divs including the:

- URL on Good Reads 
- Image for the book, you can grab from Good Reads via the "enlarge cover" and set it to a 600 X 600 image! You can use [Resize Image](https://resizeimage.net/), set the image to 600 X 600 and click "fill background to white
- The name of the book
- The author of the book
- Add the order number incrementing each `div` based on latest number e.g. 7, 8


```
<!-- Race After Technology: Abolitionist Tools for the New Jim Code  -->
<div class="grid-column span-half pt3 pb3 mobile-m order-5 reveal-on-scroll is-revealing">
    <div class="relative">
        <a hrf="https://www.goodreads.com/book/show/42527493-race-after-technology"><img class="info-image relative z2" src="/img/race-after-technology.png" alt="Race After Technology: Abolitionist Tools for the New Jim Code"></a>
        <div class="pattern pattern--left-up absolute z1"></div>
    </div>
</div>
<div class="grid-column span-half pt3 pb3 mobile-m order-6">
    <h3>Race After Technology: Abolitionist Tools for the New Jim Code </h3>
    <h4>by Ruha Benjamin </h4>
</div>
```

This project uses Netlify and will build the preview to confirm all is well! 

## Instructions
For local development, run `npm install` on the main directory and then `gulp` to get BrowserSync going along with all the Gulp tasks (see [Pear](https://github.com/jrdnbwmn/Pear)).

Development files are in `src`. Everything is compiled into `dist`—that’s where all your final files reside.

## Acknoowledgements

Theme designed by:

[Papaya](https://www.papayatemplates.com)
[@jrdnbwmn](https://www.twitter.com/jrdnbwmn)

Demo images from [Unsplash](https://unsplash.com/).
Icons from [Entypo](http://entypo.com/).