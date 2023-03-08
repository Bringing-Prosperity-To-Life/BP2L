
 #  Bringing Prosperity To Life© ( BP2L© ) 
 
 #  This is the personal base setup of Venus Katelin Martinez© for an HTML Document. ( contact anytime at v.martinez@bp2l.co )

   As with most HTML Documents, I start with...

`<!DOCTYPE html>`

   Then I proceed to the HTML tag itself, in mine I have "lang=en,es" meaning language is set to both the English Language as well as Spanish (Español), but this is not required. It doesn't do much, so if you want you could leave it written as "html".

` <html lang="en,es">`

   After the HTML tag comes the "head" tag which marks the beginning of your webpage officially and it is where things like the Title (which is usually right after the "head" tag), Link References, Stylesheets (or Tags), and other such useful information go.
```
<head>
   <title>
       <a href="https://bp2l.co">Bringing Prosperity To Life</a> Test Page
   </title>
```
   After that comes tags like "meta" which , according to Google Developers, is described as: "...HTML tags used to provide additional information about a page to search engines and other clients. Clients process the meta tags and ignore those they don't support. meta tags are added to the <head> section of your HTML page and generally look like this: <! DOCTYPE html>"

  `<meta charset="utf-8">`

## <em>  At this point you now have options as to how to build your Webpage of either a Stylesheet seperate from the html document or you can use the "style" tag.</em>

  `<link rel="stylesheet" href="\\yourStyleSheet.css">`

## <em> Or... </em>
   ~ notice how I used, different ways to write colors...

  ```
  <style>
     title {
      font-size: 27 px;
      background-color: #E01F01;
      color: darkcyan
     },

     head {
      font-size: 25 px;
      background-color: #E01F01;
      color: black;
      align-content: center;
      font-family:Times,'Times New Roman', sans-serif
     },

     .prHeading {
      border: 7px outset #F0F101;
      background-color: rgb( 152, 69, 7 );
      text-align: left;
      padding-left: 20px
     }
    </style>
```
   You can add a lot more to that and usually do, but hopefully this gives a starting point for that section too!
   We then ahave made it to the end of the "head" tag and the beginning of the "body" tag. This is your main stuff. But as this is probably the most gone over section, I'll only cover a couple things right now.
   "div" basically marks the beginning of a new style, class or even just the start of a new paragraph. It can be used to change font, color and more in text and background by using the class or style designations, or when just for breaking up a paragraph it usually ends up looking more like this:
```
   ...was no more!</span>
 </div>
 <br>
 <div>
   <span style="color: rgb( 0, 0, 0 )"...
```
So now that we have "div" explained a little bit, we can go back to where we left off, the example of what (the skeleton) of the body looks like following the ending of the "head".
```
   </head>
   <body>
    <div class="prHeading">
    <h1>Primary Heading</h1>
     <p> </p>
    <h2> </h2>
     <p> </p>
    <h3> </h3>
     <p> </p>
   </body>
```
The footer is one thing not really gone over all too much, and why? Because there really isn't much to go over. It's a section at the bottom if the page that is mostly used for those parts of the document that need to be in there for anyone who wants or needs to access it, but generally doesn't get used to often besides maybe a Home link or Navigation Menu, (those are usually in the header, though do have cases in which they flip or even occupy both). 
When it comes to the Footer that's the best place in my opinion to play around (to a point) with code or styles (that you are familiar with, but) that maybe you don't know the exact outcome. You can treat it as equal or greater than the header or you can totally scrape it and not use it at all!  but here's a really basic version that can be found many other places online I am sure.
  ```
 <footer>
    <div style="align-text: left">
     <title>Bringing Prosperity To Life© Test Page</title>
    </div>
    <div style="align-text: right">
     <f>Made By Vkmartinez95©</f>
   </footer>
  </html>
```
And then of course, you want to be sure that you end the page with the closing tag for the HTML.
I hope this helps some people to learn HTML at least a little bit! 
**I do NOT** claim to be an expert or anywhere even close. I do NOT offer any warranty nor shall I be held accountable for any damages, losses or otherwise negative circumstance that may occur as a result of using this code in any form. If you would like to know anything about responsibilities of "You" (the User, Reader, and / or Modifier of this product), "Me" (the "Original Owner"), or any other involved party, and other such legal topics, you may refer to the Vkmartinez95© License V. 1.0. (or the most up-to-date version), excluding (where applicable) the part in which it says :
  ```
The Original Owner hereby grants You a world-wide, rights-managed 
(conditional: royalties paid to the Original Owner at a 10% value rate
[monetary] when income is generated by any assets whether current,
non-current, tangible, intangible, operating or non-operating, non-
exclusive to profited income), non-exclusive license:
```

### Copyright © 2023 Vkmartinez95©
<em>This Copyright Notice is different from other Copyright notices with other material made by me, because this is one material with a little more leniency towards those who are trying to learn how to code. </em>
### <em> Unlike the other material made under this company, this Copyrighted (©) Material is Free for anyone to use, up unto the point in which this code is used to make a profit, then the royalties paid will be in percentage of how big the contribution is in relation to the size the product or software (or other sellable item that needs this code now or in the future), but no less than 5% royalties-paid to Venus Katelin Martinez©.</em>
* <em>In essence, this is meant to be a free learning template, but will require payout if profit is made from the use of this code.</em>
