# Basic HTML and HTML5

## How to use

- Search the title of the challenge by pressing Ctrl + F for the solution

## Links

You can connect with CoderApex on the following platforms:  
[Website - CoderApex.com](https://www.coderapex.com/)  
[YouTube Channel - CoderApex](https://www.youtube.com/channel/UCBerXSfE4lrd3E0oFJqrYCQ)  
[Instagram - CoderApex](https://www.instagram.com/coderapex/)  
[Facebook Page - CoderApex](https://www.facebook.com/coderapex/)

## Solutions

List of solutions organized by sections.

### Section: Basic HTML and HTML5

#### Say Hello to HTML Elements

##### Challenge:

To pass the test on this challenge, change your h1 element's text to say "Hello World".

##### Solution:

```html
<h1>Hello World</h1>
```

#### Headline with the h2 Element

##### Challenge:

Add an h2 tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" h1 element.

##### Solution:

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
```

#### Inform with the Paragraph Element

##### Challenge:

Create a p element below your h2 element, and give it the text "Hello Paragraph".

##### Solution:

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
```

#### Fill in the Blank with Placeholder Text

##### Challenge:

Replace the text inside your p element with the first few words of this kitty ipsum text: Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.

##### Solution:

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

#### Uncomment HTML

##### Challenge:

Uncomment your h1, h2 and p elements.

##### Solution:

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

#### Comment out HTML

##### Challenge:

Comment out your h1 element and your p element, but not your h2 element.

##### Solution:

```html
<!--
<h1>Hello World</h1>
-->
<h2>CatPhotoApp</h2>
<!--
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
-->
```

#### Delete HTML Elements

##### Challenge:

Delete your h1 element so we can simplify our view.

##### Solution:

```html
<h2>CatPhotoApp</h2>

<p>
  Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack
  your ankles chase the red dot, hairball run catnip eat the grass sniff.
</p>
```

#### Introduction to HTML5 Elements

##### Challenge:

Create a second p element after the existing p element with the following kitty ipsum text: Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.

Wrap the paragraphs with an opening and closing main tag.

##### Solution:

```html<h2>CatPhotoApp</h2>
<main>
  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>

  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

#### Add Images to Your Website

##### Challenge:

Let's try to add an image to our website:

Insert an img tag, before the h2 element.

Now set the src attribute so that it points to this url:

https://bit.ly/fcc-relaxing-cat

Finally don't forget to give your image an alt text.

##### Solution:

```html
<img src="https://bit.ly/fcc-relaxing-cat" alt="Image of a cute relaxing cat" />

<h2>CatPhotoApp</h2>

<main>
  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

#### Link to External Pages with Anchor Elements

##### Challenge:

Create an a element that links to http://freecatphotoapp.com and has "cat photos" as its anchor text.

##### Solution:

```html
<h2>CatPhotoApp</h2>

<main>
  <a href="http://freecatphotoapp.com">cat photos</a>

  <img
    src="https://bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

#### Link to Internal Sections of a Page with Anchor Elements

##### Challenge:

Change your external link to an internal link by changing the href attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".

Remove the target="\_blank" attribute from the anchor tag since this causes the linked document to open in a new window tab.

Then add an id attribute with a value of "footer" to the <footer> element at the bottom of the page.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <a href="#footer">Jump to Bottom</a>

  <img
    src="https://bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed
    everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum
    dolor sit amet, shed everywhere shed everywhere stretching attack your
    ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump
    eat the grass rip the couch scratched sunbathe, shed everywhere rip the
    couch sleep in the sink fluffy fur catnip scratched.
  </p>
  <p>
    Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch
    at owner, destroy all furniture, especially couch or lay on arms while
    you're using the keyboard. Missing until dinner time toy mouse squeak roll
    over. With tail in the air lounge in doorway. Man running from cops stops to
    pet cats, goes to jail.
  </p>
  <p>
    Intently stare at the same spot poop in the plant pot but kitten is playing
    with dead mouse. Get video posted to internet for chasing red dot leave fur
    on owners clothes meow to be let out and mesmerizing birds leave fur on
    owners clothes or favor packaging over toy so purr for no reason. Meow to be
    let out play time intently sniff hand run outside as soon as door open yet
    destroy couch.
  </p>
</main>

<footer id="footer">Copyright Cat Photo App</footer>
```

#### Nest an Anchor Element within a Paragraph

##### Challenge:

Now nest your existing a element within a new p element (just after the existing main element). The new paragraph should have text that says "View more cat photos", where "cat photos" is a link, and the rest of the text is plain text.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>
    View more
    <a href="http://freecatphotoapp.com" target="_blank">cat photos</a>
  </p>

  <img
    src="https://bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```

#### Make Dead Links Using the Hash Symbol

##### Challenge:

The current value of the href attribute is a link that points to "http://freecatphotoapp.com". Replace the href attribute value with a #, also known as a hash symbol, to create a dead link.

For example: href="#"

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>

  <img
    src="https://bit.ly/fcc-relaxing-cat"
    alt="A cute orange cat lying on its back."
  />

  <p>
    Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching
    attack your ankles chase the red dot, hairball run catnip eat the grass
    sniff.
  </p>
  <p>
    Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere
    rip the couch sleep in the sink fluffy fur catnip scratched.
  </p>
</main>
```
