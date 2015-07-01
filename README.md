## Part One - Landing With Bootstrap

 1. Open `landing_start.html` in Chrome and Sublime. Open `landing_target.html` in Chrome.
 1. In `landing_start`, remove the `<link>` to `my_landing_styles.css`. We've now wiped out all of the hard work we did last time. Refresh in Chrome to see what we're left with.
 1. Now, let's connect the document to `bootstrap.css`, which I have already downloaded into a subfolder called `assets/css`. Add this line to the `<head>`:

        <link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
 
 1. Try to modify the starting point until it looks like the target:
  - Replace the `<table></table>` element we hijacked for layout with a `<div class="container"></div>` element.
  - Wherever we had `<tr></tr>` elements, replace them with `<div class="row"></div>` elements.
  - Wherever we had `<td></td>` elements, replace them with `<div class="col-md-X"></div>` elements where `X` is a number between 1 and 12 (however many columns you want that cell to span across).
  - Now that we're done positioning, let's do some styling:
    - [Button classes](http://getbootstrap.com/css/#buttons)
    - [Jumbotron component](http://getbootstrap.com/components/#jumbotron)

## Part Two - Roster With Bootstrap

 1. Open `roster_start.html` in Chrome and Sublime. Open `roster_target.html` in Chrome.
 1. In `roster_start`, delete everything inside the `<head>` tag except for the `<title>`. We've now wiped out all of the hard work we did last time. Refresh in Chrome to see what we're left with.
 1. Now, let's connect the document to `bootstrap.css`, which I have already downloaded into a subfolder called `assets/css`. Add this line to the `<head>`:

        <link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
 
 1. Try to modify the starting point until it looks like the target:
  - Replace the `<table></table>` element we hijacked for layout with `<div class="container"></div>` element.
  - Wherever we had `<tr></tr>` elements, replace them with `<div class="row"></div>` elements.
  - Wherever we had `<td></td>` elements, replace them with `<div class="col-md-X"></div>` elements where `X` is a number between 1 and 12 (however many columns you want that cell to span across).
  - Now that we're done positioning, let's do some styling:
    - [list-unstyled class](http://getbootstrap.com/css/#unstyled)
    - [img-rounded class](http://getbootstrap.com/css/#images-shapes) (instead of our old `"avatar-image"` class)
    - [Panel component](http://getbootstrap.com/components/#panels) (instead of our old `"card"` class)
    - [Page header component](http://getbootstrap.com/components/#page-header)

## Part Three - Canvas Positioning

 1. Open `canvas_positioning_start.html` in Chrome and Sublime. Open `canvas_positioning_target.html` in Chrome.
 1. Use [Shoelace.io](http://shoelace.io/) to plan out your layout. Copy the skeleton code into your document from Shoelace.
 1. Move the content up into the right spots in the skeleton.
 1. Apply styles as needed.

## Part Four - Canvas Styling

Bootstrap gives us a great foundation, but we usually have to write some of our own custom styles, too. We can link our own custom stylesheet below the link to Bootstrap and customized/override whatever we wish.


## Part Five - Essential HTML

Read through `details.html`, `index.html`, and `new.html` and try to make sense of them. Open them in Chrome and play with them. Write down any questions you have about anything at all in them.

This is all you **need** to know for now.
