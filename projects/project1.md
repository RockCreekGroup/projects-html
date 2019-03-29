# Project 1
Welcome to the entry point for your project work for RockCreek. We're glad you made it this far! And just to be sure, you've already read and followed the instructions in the [Readme](https://github.com/RockCreekGroup/projects-html), right? And you're on a separate branch than master? 

Ok, good.

## Step 1: Include RockCreek's Standard CSS
First and foremost, you'll need to create a new file. Name it investments.html. Obviously, index.html is a little more common, as browsers know to load that file if it's in a web server's home directory, but it's easy enough to load investments.html. And you guessed it, there will be more HTML files in future projects to come.

Second, you'll need to insert the HTML required to load the RockCreek CSS. The file you want is in this repo's [css/](https://github.com/RockCreekGroup/projects-html/tree/master/css) directory and is named rockcreek.css.

## Step 2: Include a header and footer
There are header and footer elements defined in the CSS.  They should be used! Using header and footer HTML elements, add both to your page. You should be able to verify that they are styled. If you don't get any style, then something is wrong. Figure out what!

## Step 3: Create a list of investors
Now you should be ready to create a list of inveztments. For now, all that you want to show in that list is the name of the investment, the name of the firm that holds the investment, and the [AUM of the investment](https://www.investopedia.com/terms/a/aum.asp).

Here's some sample data you can use:
```
| Investment                       | Firm                    | AUM      |
| -------------------------------- | ----------------------- | -------- |
| Pear Leopard Fund                | Kikuchi & Bartoloni LLP | 1200000  |
| Sapphire Queen Parrotfish Fund   | Tapinassi & Mistry Ltd. | 543124   |
| Burgundy Bluefish Fund           | Fraser & Köhler LLP     | 2543098  |
| Raspberry Pigeons Fund           | Tapinassi & Mistry Ltd. | 1111223  |
| Teal Angelfish King Fund         | Kikuchi & Bartoloni LLP | 982988   |
| Cerise Caribbean Flamingo Fund   | Kikuchi & Bartoloni LLP | 12003123 |
| Prussian Blue Geese Fund         | Dupuis & Giannoni Ltd.  | 2098123  |
| Taupe Radiated Tortoise Fund     | Kikuchi & Bartoloni LLP | 4320121  |
```

A few notes you should probably take into account:
- A list on an HTML page doesn't always have to use the ul, ol, and li elements. It can, but it doesn't have to.
- AUM (assets under management) is a dollar figure. This should be reflected on the page.
- The CSS you referenced might have some helpful clues as to what elements are pre-styled. Maybe take a peek?