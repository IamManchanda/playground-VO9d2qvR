# Part 1 - Conceptual Introduction to Modern CSS Building Blocks

This article is **Part 1** for the series **“Flexbox and CSS Grid”.**

![](https://d2mxuefqeaa7sj.cloudfront.net/s_F071818CF3B1B881349F6958DF895F7616D0300F6FAAC823C908F39300A5A9EF_1507716842225_cover-1.png)

CSS Grid vs Flexbox? Wait! They are not competitors and meant to be work together. A grid item can be a flex container, a flex item can be a grid container. At the end of the day, Flexbox has some stuff that Grid can't-do and Grid Spec has some stuff that Flexbox can't-do. They have a common box model which help us align both of these modern Building Blocks. My Advice, use them together and enjoy the web! 

In this article series, we will first look to learn flexbox (one dimensional) with some interactive examples. Then, we will look to do the same with CSS Grid (two dimensional), but will also discuss the browser support. 

That said, there is no need for any discussion for the browser support for flexbox as it’s has great [browser support](http://caniuse.com/#feat=flexbox) considering it is so new. Moreover, Microsoft decision to stop [support](https://www.microsoft.com/en-in/windowsforbusiness/end-of-ie-support) for old versions of IE that don’t support flexbox makes it’s case even more powerful.

## What is this Flexbox Anyway?

If you are looking for elements to behave predictably in your page layout where it accommodates to the different screen sizes and different display devices to fill the available space based on the design as best it could, then what you need is Flexbox. Flexbox consists of flex containers and flex items.

A flex container contains one or more flex Items. Flexbox is designed for laying out complex applications and web pages. Please note that everything that is outside a flex container or even nested inside a flex item will be rendered as usual. 

> The CSS Flexible Box Module Level1, or flexbox for short, makes the once-difficult task of laying out your page, widget, application, or gallery almost simple. With flexbox, layout is so simple you won’t need a CSS framework. Widgets, carousels,responsive features—whatever your designer dreams up.

Yes, Finally CSS has an update that will make your lives easier. Now, you don’t have to face the challenges of creating layouts with floats and padding and instead it lets you specify containers and their contents instead. This new model would mean that you can now specify the directions in which material flows, how content wraps, and the ways components can expand to fill a space. Whether you've been creating large sites or small, fixed sites or responsive sites, flexbox will surely simplify your work.

Flexbox is arguably similar to the block layout, though lacks many CSS properties that are used within a block layout, like floats and columns. But hey, it has that more and more flexibility for distributing space and aligning content in many possible ways that web applications and complex web pages need. It looks to solve a lot of layout problems that we are facing from a very long time like vertical centering, sticky footers, media objects, and simpler Grid Systems.

What matters the most is that the flexbox layout is **direction-agnostic** as opposed to block/inline layout mode (block is vertical, inline is horizontal). The flexibility that Block or Inline mode lacked is that they are just one direction only. Flexbox, on the other hand, is two directional. Again, not to be confused with two-dimensional, Flexbox is one-dimensional. You have to just add `flex-direction` CSS property to its values and it will do the layout as per the need.

Here's what [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) says about Flexbox,

> A new technology, but with support now fairly widespread across browsers, Flexbox is starting to become ready for widespread use. Flexbox provides tools to allow rapid creation of complex, flexible layouts, and features that historically proved difficult with CSS. This article explains all the fundamentals.

Yes, I would agree that Flexbox is surely tough to grasp, I had that same feeling not a long while back and even today I get confused, on what combination of properties you need to let it do what you want in your web design. In coming articles, we will look to discuss the core fundamentals of Flexbox so that you can understand, what these flexbox properties really do and how you can use them for your next awesome website. Apart from covering the fundamentals, we will also cover some examples through which I would hope that you can understand more and more about the **Present** of the web, **Flexbox**.

## What is this CSS Grid Anyway?

CSS Grid Layout Working Draft was published back in April 2011. That time, three of the four authors were from Microsoft and the first IE10 Platform Preview shipped with a -ms prefixed Grid implementation. Time has passed by and over the course of these 7 years, Grid spec has evolved based on feedback from developers and browser vendors working together to come up with a truly effective native CSS grid solution.

The CSS Grid layout shines at dividing a page into major areas or establishing the connection in terms of size, position, and layer, between parts of a control built from HTML primitives.

Like tables, the grid layout enables us to align elements into columns and rows. However, many more layouts are either possible or easier with CSS grid than they were with tables. For example, a grid container's child elements could position themselves so they actually overlap and layer, similar to CSS positioned elements.

CSS Grid comes up with a series of properties that allow us to create grid structures and control the placement and sizing of grid items using CSS. This would mean that we are able to use media queries to adapt our grids to different contexts. We can then rearrange the layout of grid items independent of their source order, which thankfully allows us to shift those grid items around to cater for these varying contexts without any need to change the underlying markup.

As Grid is created to be very flexible and provide solutions for many different use cases, please note that it is not something that you can just pick up and use within a day. It won't happen but that said if you give learning the Grid Spec a proper time, once you get the hang of it, you’ll be able to spend more time on designing layouts instead of wrangling code and thus produce the layout you want with ease thanks to **Future** of the web, CSS Grid.

## Flexbox and CSS Grid: What it means to a Designer?

CSS, yes that boring 90's CSS has come a long way since its introduction. But the tools we had available for layout, frankly speaking there was no fun to talk about. Table layouts were incredibly too rigid, float-based layouts were basically a hack, positioning-based layouts were not adaptable, and none could handle a great deal of complexity in an efficient way. Yes, it's true that these methods got us really far, the whole current web is made from them. Isn't it? But that said, they are not intended for complex layout purposes.

Embracing the fluidity of a website design is crucial to a responsive web design and thus has made things more obvious regarding the short-comings of these old methods for layout. Come flexbox and CSS Grid, at last we now have the tools that are intended specifically for the layout and is more efficient and that too without any hacks needed like their former layout methods. We can now easily solve those real problems that we face day in, day out with responsive web design.

## To be Continued…

Thanks for following along. Yes no, code practise in this article but I promise this will be the only article in the series that doesn’t have code practise. We will doing lot of coding practise so get ready with all guns blazing. [Next](https://tech.io/playgrounds/7394/flexbox-and-css-grid-part--2) up is **Part 2,** where we will cover the **Flex container**.

## References
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes
- https://tympanus.net/codrops/css_reference/flexbox/
