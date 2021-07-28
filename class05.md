# HTML

# Images

## HTML Images Syntax

The HTML < img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The < img> tag creates a holding space for the referenced image.

The < img> tag is empty, it contains attributes only, and does not have a closing tag.

The < img> tag has two required attributes:

* src - Specifies the path to the image
* alt - Specifies an alternate text for the image

**Syntax**

< img src="url" alt="alternatetext">


## The src Attribute

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

**Example**

< img src="img_chania.jpg" alt="Flowers in Chania">


## The alt Attribute

The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

**Example**

< img src="img_chania.jpg" alt="Flowers in Chania">



# Color

![dd](https://www.w3schools.com/colors/img_colormap.gif)


![h](https://i0.wp.com/codeexercise.com/wp-content/uploads/2017/12/HTMLcolors.png?fit=857%2C396&ssl=1)


![g](https://www.programmersought.com/images/767/2ff5a1539fb5cf49f6a96f3945a8af1f.png)


# Text 

## HTML Formatting Elements

Formatting elements were designed to display special types of text:

* **< b>** - Bold text

* **< strong>** - Important text

* **< i>** - Italic text

* **< em>** - Emphasized text

* **< mark>** - Marked text

* **< small>** - Smaller text

* **< del>** - Deleted text

* **< ins>** - Inserted text

* **< sub>** - Subscript text

* **< sup>** - Superscript text

## HTML < b > and < strong > Elements

1. The HTML < b> element defines bold text, without any extra importance.

**Example**

< b>This text is bold< /b>


2. The HTML < strong> element defines text with strong importance. The content inside is typically displayed in bold.

**Example**

< strong>This text is important!< /strong>


## HTML < i> and < em> Elements

1. The HTML < i> element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

Tip: The < i> tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

**Example**

< i>This text is italic< /i>

2. The HTML < em> element defines emphasized text. The content inside is typically displayed in italic.

Tip: A screen reader will pronounce the words in < em> with an emphasis, using verbal stress.

**Example**

< em>This text is emphasized< /em>


## HTML < small> Element

The HTML < small> element defines smaller text:

**Example**

< small>This is some smaller text.< /small>

## HTML < mark> Element

The HTML < mark> element defines text that should be marked or highlighted:

**Example**

< p>Do not forget to buy < mark>milk< /mark> today.< /p>

## HTML < del> Element

The HTML < del> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

**Example**

< p>My favorite color is < del>blue< /del> red.< /p>

## HTML < ins> Element

The HTML < ins> element defines a text that has been inserted into a document. Browsers will usually underline inserted text:

**Example**

< p>My favorite color is < del>blue< /del> < ins>red< /ins>.< /p>


## HTML < sub> Element

The HTML < sub> element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

**Example**

< p>This is < sub>subscripted< /sub> text.< /p>


## HTML < sup> Element

The HTML < sup> element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]:

**Example**

< p>This is < sup>superscripted< /sup> text.< /p>





# JPEG vs PNG vs GIF

# which image format to use and when?

1. **TL;DR**

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.


2. **Compression**

JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality.


3. **Transparency**

In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.

* **JPEG** images don’t support transparency and are hence not usable for such cases.


* **PNG** images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). 


* **GIF** images support transparency by declaring a single colour in the colour palette as transparent (index transparency). 


4. **Colours**

There is a significant difference in the number of colours that can be supported by these 3 formats.


* **JPEG** images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.


* **PNG** images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.


* **GIF** images are limited to 256 colours. If index transparency is used, then one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours.


5. **Animation**

Animation, in this case, refers to any change or movement in the image. It doesn’t necessarily have to have frame rates like an animated video, but essentially a part or the entire image changes with time.


**For more information** [Click Here](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)




