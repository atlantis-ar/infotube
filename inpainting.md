# Image inpainting
### _Early era_
Image inpainting has been a cornerstone process in the history of art, aiming to fill damaged, deteriorating or even missing pieces of an artowork, while trying to mimic the original content, and when it is not available, respect the style of the piece of art. 

![](https://github.com/atlantis-ar/notes/blob/main/assets/img/image_inpainting/oil_painting_restoration.jpeg)
<center>
*Oil painting restoration*
</center>

### _Industrial era_
With the advent of technology people enjoyed a more intermediate,accurate and faster way of depicting reality, the _photography_. Along with the rapid spread of _photography_ throughout the population, came an even greater need for restoring and even sometimes complete images, since it came with a lot of caveats (exposure, high noise and more), especially in the earlier days.

![](https://github.com/atlantis-ar/notes/blob/main/assets/img/image_inpainting/black_n_whie_restoration.jpg)
<center>
*Image restoration example taken from [wikipedia](https://en.wikipedia.org/wiki/File:Restoration.jpg)*
</center>

## _Information age_
Over the last few decades, technological leaps have enabled the world-wide, cheap and efficient usage of commodity cameras, as well as the extensively used _digital image processing_ field. This field opened up countless new possibilities on image processing, especially in the inpainting or restoration tasks.

![](https://github.com/atlantis-ar/notes/blob/main/assets/img/image_inpainting/object_removal.jpg)
<center>
*Object removal example, at first removal of the object (middle) and subsequently inpainting (right)
</center>

![](https://github.com/atlantis-ar/notes/blob/main/assets/img/image_inpainting/face_inpainting.jpg)
<center>
*Object removal example, complete generation of face*
</center>




# Diminished Reality (DR) vs Image Inpainting
As previously explained, Diminished Reality (DR from now on), aims to create a simplified yet realistic representation of our world (very similar to object removal). So can be DR be realised with classical image inpainting as it has beed showcased above? Sadly the answer is both **yes** and **no**, or in one word **depends**. Let's dive in further in this answer.

## **Yes**, DR can be solved with classical image inpainting.
Taking some of the shelf, state-of-the art, methods and using them in a DR context is a fully viable solution, since once an object will be selected and erased, it will be by a fully realistic patch, some times really _indistinguishable_ and _realistic_ from the rest of the image. In more detail, _indistinguishable_ is used in more of _the style of the patch is highly coherent to the rest of the image_, so yes we can use it.

## **No**, DR is more of a just realism.
The word _indistinguishable_ has nothing to do with reality or true representation of the world, it refers more to the style of the overal image, rather that the context. In other words, nothing stops the image inpainters to produce results that make no sense (floating trees or dragons). So here is the major distinction in the word _realistic_ and _reality_. Classical image inpainting covers the _realistic_ part of the problem while has no guarantees for the _reality_ part.


