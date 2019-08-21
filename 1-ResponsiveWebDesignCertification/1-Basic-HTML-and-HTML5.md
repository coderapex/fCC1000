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

#### Turn an Image into a Link

##### Challenge:

Place the existing image element within an anchor element.

Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

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

#### Create a Bulleted Unordered List

##### Challenge:

Remove the last two p elements and create an unordered list of three things that cats love at the bottom of the page.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <ul>
    <li>Wool</li>
    <li>Lasers</li>
    <li>Milk</li>
  </ul>
</main>
```

#### Create an Ordered List

##### Challenge:

Create an ordered list of the top 3 things cats hate the most.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>

  <p>Top 3 things cats hate:</p>
  <ol>
    <li>Water</li>
    <li>Dogs</li>
    <li>Cold Milk</li>
  </ol>
</main>
```

#### Create a Text Field

##### Challenge:

Create an input element of type text below your lists.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>

  <input type="text" />
</main>
```

#### Add Placeholder Text to a Text Field

##### Challenge:

Set the placeholder value of your text input to "cat photo URL".

##### Solution:

```html
<h2>CatPhotoApp</h2>
<li>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text" placeholder="cat photo URL" />
</li>
```

#### Create a Form Element

##### Challenge:

Nest your text field inside a form element, and add the action="/submit-cat-photo" attribute to the form element.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>

  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" />
  </form>
</main>
```

#### Add a Submit Button to a Form

##### Challenge:

Add a button as the last element of your form element with a type of submit, and "Submit" as its text.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" />
    <button type="submit">Submit</button>
  </form>
</main>
```

#### Use HTML5 to Require a Field

##### Challenge:

Make your text input a required field, so that your user can't submit the form without completing this field.

Then try to submit the form without inputting any text. See how your HTML5 form notifies you that the field is required?

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required />
    <button type="submit">Submit</button>
  </form>
</main>
```

#### Create a Set of Radio Buttons

##### Challenge:

Add a pair of radio buttons to your form, each nested in its own label element. One should have the option of indoor and the other should have the option of outdoor. Both should share the name attribute of indoor-outdoor to create a radio group.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<label>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required />

    <label for="indoor">
      <input id="indoor" type="radio" name="indoor-outdoor" />Indoor
    </label>

    <label for="outdoor">
      <input id="outdoor" type="radio" name="indoor-outdoor" />Outdoor
    </label>

    <button type="submit">Submit</button>
  </form>
</label>
```

#### Create a Set of Checkboxes

##### Challenge:

Add to your form a set of three checkboxes. Each checkbox should be nested within its own label element. All three should share the name attribute of personality.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label for="indoor"
      ><input id="indoor" type="radio" name="indoor-outdoor" /> Indoor</label
    >
    <label for="outdoor"
      ><input id="outdoor" type="radio" name="indoor-outdoor" /> Outdoor</label
    ><br />
    <input type="text" placeholder="cat photo URL" required />
    <button type="submit">Submit</button>

    <label for="happy">
      <input type="checkbox" id="happy" name="personality" />Happy
    </label>
    <label for="fussy">
      <input type="checkbox" id="fussy" name="personality" />Fussy
    </label>
    <label for="cranky">
      <input type="checkbox" id="cranky" name="personality" />Cranky
    </label>
  </form>
</main>
```

#### Check Radio Buttons and Checkboxes by Default

##### Challenge:

Set the first of your radio buttons and the first of your checkboxes to both be checked by default.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<label>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked /> Indoor</label>
    <label><input type="radio" name="indoor-outdoor" /> Outdoor</label><br />
    <label><input type="checkbox" name="personality" checked /> Loving</label>
    <label><input type="checkbox" name="personality" /> Lazy</label>
    <label><input type="checkbox" name="personality" /> Energetic</label><br />
    <input type="text" placeholder="cat photo URL" required />
    <button type="submit">Submit</button>
  </form>
</label>
```

#### Nest Many Elements within a Single div Element

##### Challenge:

Nest your "Things cats love" and "Things cats hate" lists all within a single div element.

Hint: Try putting your opening div tag above your "Things cats love" p element and your closing div tag after your closing ol tag so that both of your lists are within one div.

##### Solution:

```html
<h2>CatPhotoApp</h2>
<label>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"
    ><img
      src="https://bit.ly/fcc-relaxing-cat"
      alt="A cute orange cat lying on its back."
  /></a>

  <div>
    <p>Things cats love:</p>
    <ul>
      <li>cat nip</li>
      <li>laser pointers</li>
      <li>lasagna</li>
    </ul>
    <p>Top 3 things cats hate:</p>
    <ol>
      <li>flea treatment</li>
      <li>thunder</li>
      <li>other cats</li>
    </ol>
  </div>
  <form action="/submit-cat-photo">
    <label><input type="radio" name="indoor-outdoor" checked /> Indoor</label>
    <label><input type="radio" name="indoor-outdoor" /> Outdoor</label><br />
    <label><input type="checkbox" name="personality" checked /> Loving</label>
    <label><input type="checkbox" name="personality" /> Lazy</label>
    <label><input type="checkbox" name="personality" /> Energetic</label><br />
    <input type="text" placeholder="cat photo URL" required />
    <button type="submit">Submit</button>
  </form>
</label>
```

#### Declare the Doctype of an HTML Document

##### Challenge:

Add a DOCTYPE tag for HTML5 to the top of the blank HTML document in the code editor. Under it, add opening and closing html tags, which wrap around an h1 element. The heading can include any text.

##### Solution:

```html
<!DOCTYPE html>
<html>
  <h1>H1 Element</h1>
</html>
```

#### Define the Head and Body of an HTML Document

##### Challenge:

Edit the markup so there's a head and a body. The head element should only include the title, and the body element should only include the h1 and p.

##### Solution:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>The best page ever</title>
  </head>
  <body>
    <h1>The best page ever</h1>
    <p>
      Cat ipsum dolor sit amet, jump launch to pounce upon little yarn mouse,
      bare fangs at toy run hide in litter box until treats are fed. Go into a
      room to decide you didn't want to be in there anyway. I like big cats and
      i can not lie kitty ipsum dolor sit amet, shed everywhere shed everywhere
      stretching attack your ankles chase the red dot, hairball run catnip eat
      the grass sniff. Meow i could pee on this if i had the energy for slap
      owner's face at 5am until human fills food dish yet scamper. Knock dish
      off table head butt cant eat out of my own dish scratch the furniture.
      Make meme, make cute face. Sleep in the bathroom sink chase laser but pee
      in the shoe. Paw at your fat belly licks your face and eat grass, throw it
      back up kitty ipsum dolor sit amet, shed everywhere shed everywhere
      stretching attack your ankles chase the red dot, hairball run catnip eat
      the grass sniff.
    </p>
  </body>
</html>
```
